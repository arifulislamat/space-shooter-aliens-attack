# space-shooter-aliens-attack 🚀
I have developed this game a long time ago, i thought it is a good idea to make it opensource, maybe newcomers find it interesting.

# Desktop build guide 🖥
- Install Construct 2 ( look at engine dir)
- Add the licence 
- Install [nwjs](https://www.scirra.com/nwjs)
- Contruct 2 > Export > Desktop 

# Android build guide 📱 

- Export your project from construct 2 with cordova 
- Install Java [JDK 8](https://www.openlogic.com/openjdk-downloads?field_java_parent_version_target_id=All&field_operating_system_target_id=All&field_architecture_target_id=All&field_java_package_target_id=All&page=1)
- Install [Node.js](https://nodejs.org/en/download/)
- Install [Android Studio](https://developer.android.com/studio)
- Install Cordova plugin 
` npm install -g cordova`
- Create cordova project
` cordova create project_name com.arifulislamat.ssaa project_name`
- Goto ` project_name\platforms\android\app\src\main\assets\www` 
- and copy paste everything from exported www dir to new www
- Open android studio and import `project_name\platforms\android`
- Install required Android SDK
- Great now just build the apk.
