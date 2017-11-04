# suisjeantisemite-mobile

If you want to make you html/css/js app a mobile app run by Node.js:
 - install android sdk (android studio), android sdk will be installed in "C:\Users\zg2pro\AppData\Local\Android\Sdk\tools"
 - run Android/Sdk/tools/bin/sdkmanager --licenses and answer yes to all licenses
 - npm install cordova -g
 - cordova create suisjeantisemite-mobile com.github.zg2pro.suisjeantisemite Sja
 - cordova platform add android
 - cordova plugin add cordova-plugin-dialogs
 - cordova plugin add cordova-plugin-network-information
 - after creating a first project in android studio, you should have a target available when listing with command: SDKPATH/android list target
 - cordova emulate android + cordova run suisjeantisemite-mobile should help you emulate a mobile on your pc
 - build the project with cordova build --release then the build appears in workspace\suisjeantisemite-mobile\platforms\android\build\outputs\apk

# http://blog.sergemazille.com/serveur-web-node-js-android/ (dead link)
# https://auth0.com/blog/converting-your-web-app-to-mobile/
# http://imikado.developpez.com/tutoriels/androidCordova/ma-premier-application/

# continuous integration can be done with circleCI...