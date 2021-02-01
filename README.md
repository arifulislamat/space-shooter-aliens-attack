# space-shooter-aliens-attack
I have develop this game long time ago, i thougt its a good idea to make it opensource, maybe new commer find it intersting.

# Desktop build guide
- Install Construct 2
- Add the licence 
- Install [nwjs](https://www.scirra.com/nwjs)
# Android build guide 

- Export your project from construct 2 with cordova 
- Install Java JDK 8
- Install Node.js
- Install Cordova plugin 
` npm install -g cordova`
- Install required Android SDK
- Create cordova project
` cordova create project_name com.arifulislamat.ssaa project_name`
- Goto ` project_name\platforms\android\app\src\main\assets\www` 
- and copy paste everything from exported www dir to new www
- Open android studio and import `project_name\platforms\android`
- Great now just build the apk.
