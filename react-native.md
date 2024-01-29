1. ERROR: [!] CocoaPods could not find compatible versions for pod "Firebase/DynamicLinks": In Podfile:
   FIX:

   ```
   rm -rf node_modules
   rm -rf Pods
   rm Podfile.lock
   yarn cache clean
   rm -rf ~/.cocoapods/repos/trunk
   pod repo update
   pod install
   ```
