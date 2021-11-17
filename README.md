# Hello_world_extension
This is a Hello World chrome/ios_safari extension.


## How it works:
When we click on the extension, it pop up a textarea prompt. In the textarea, we can provide a string and the extension will show 
Hello <Provided String>


## How to setup in chrome:
  1. Go to chrome://extensions/ 
  2. Enable Developer Mode
  3. Click on `Load Unpacked`
  4. Select the path for folder which contains `manifest.json`
  
  
## How to setup in ios simulator:
  1. Go to xcode
  2. Open `safari/Hello World/Hello World.xcodeproj`
  3. Choose an ios version for simulator
  4. Start the active scheme (or Build the xcode)  
  
  
  Update the AWS configs accordingly.
  
## How to add the App in Bitrise
  1. Open https://app.bitrise.io/
  2. Login/Sign-up
  3. Click on `Add new app`
  4. Choose an account and set the privacy of the app
  5. Connect to `GitHub`
  6. Select the repository with the extension -- `hello_world_ios`
  7. Click on `Auto-add SSH Key`
  8. Choose the branch -- `main`
  9. Select the `Scheme name` in project build configuration
  10. Select the `Distribution method`
  11. Choose the App icon
  12. Click on `Register a webhook for me`
  13. Click on build
  14. Click on `Edit Workflow`
  15. Select `bitrise.yml`
  16. Click on `Store in app Repository`
  17. Click on `update the settings`
  18. Click on `Continue`
  19. Rebuild
  
  DONE!!
  
  
