1. ERROR: [!] CocoaPods could not find compatible versions for pod "Firebase/DynamicLinks": In Podfile:
   FIX:

   ```
   rm -rf ~/.cocoapods/repos/trunk
   pod repo update
   pod install
   ```
