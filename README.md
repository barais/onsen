# onsen

## Step 0
Please install JDK, Graddle, nodejs and Android SDK

## Install Monaca CLI, an Onsen UI toolkit

First install Node.js. Then, install Monaca CLI via npm, which provides command-line interface for Onsen UI development. Or, if you prefer GUI, download and install Monaca Localkit desktop app for Windows and OS X.

```bash
npm install -g monaca
```

Trouble setting up your environment? See Getting Started with Monaca Cloud IDE to start writing code right away!
Create a project

## Create Onsen UI app from starter kit. 

You can choose Onsen UI version and the framework to use.

```bash
monaca create myfirstapp
```

Select Sample apps, jQuery TODO Apps


## Run on your device

Run monaca preview to run on the browser. To run on the device, use monaca debug to run in the debugger.

```bash
cd myfirstapp
monaca preview # Preview on the browser
monaca debug # Run on the device in debugger
monaca remote build # Build the app
```

## Call a Rest Web services

Get Star Wars API info. 

http://www.swapi.co

https://www.ibm.com/developerworks/community/blogs/victorsh/entry/march_11_2014_8_58_pm?lang=en

## Install and play with a specific plugin (Connexion information)

https://docs.monaca.io/en/reference/cordova_5.2/network-information/
 


## Notes

```bash
# To start the emulators
export ANDROID_HOME=~/Android/Sdk
~/Android/Sdk/emulator/emulator -list-avds
~/Android/Sdk/emulator/emulator @Nexus_5X_API_24
```

```bash
export ANDROID_HOME=~/Android/Sdk
cordova platform add android
cordova prepare              # or "cordova build"
cordova emulate android
cordova run android --device 

```


https://cordova.apache.org/docs/fr/latest/guide/platforms/android/
http://stackoverflow.com/questions/43586765/android-emulator-running-extremly-slow-on-ubuntu-17-04-compared-to-windows-10

