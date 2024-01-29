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
