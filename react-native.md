1. ERROR: [!] CocoaPods could not find compatible versions for pod "Firebase/DynamicLinks": In Podfile:
   FIX:

   ```
   rm -rf node_modules
   cd ios
   rm -rf Pods
   rm Podfile.lock
   cd ..
   yarn cache clean
   yarn
   cd ios
   rm -rf ~/.cocoapods/repos/trunk
   pod repo update
   pod install
   ```

2. ERROR: listen EADDRINUSE: address already in use :::8081.
   FIX:
   ```
   yarn start dev --port 8082
   ```
3. ➜ Implicit dependency on target
   FIX:
   ```
   cd ios
   pod install --repo-update
   ```
   If Issue Persits such as (1)
   ``` pod update [package]```
5. 
