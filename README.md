# Smart Primer Application

This is the main smart primer application. It is developed as a web application and deployed to tablets using Cordova.

## Wiki

https://github.com/smartprimer/smartprimer-webapp/wiki

## Hosting 

The web app is hosted at http://smartprimer.org/ (contact Sherry for server username and password if you want to access the server)

## Installation 

### Add to Homescreen (not recommended)

Open the website above (http://smartprimer.org/) from the Chrome browser on a Android tablet. Click the setting button in the browser and choose "Add to Homescreen". This will automactially turn the website to an application on your Android desktop. You can start to play with the application! Make sure to turn on the volume.

### Cordova (recommended)

Make sure you have all the requirements satisfied. Connect your tablet with your computer. Go to the cordova folder and run `cordova run android --device`.

## Cordova Requirements

1. Install npm if you don’t have it. The recommended way is to download Node.js (9.6.1 current) from https://nodejs.org/en/.

2. Follow instructions at https://cordova.apache.org/#getstarted to install Cordova. (Stop when you successfully install Cordova. You don’t need to create a new cordova repository.)

3. Install Android SDK. The recommended way is to install android studio (https://developer.android.com/studio/index.html)

4. Check your JDK version by typing `java -version`. If it’s not 1.8, uninstall it (for uninstallation instructions see https://docs.oracle.com/javase/8/docs/technotes/guides/install/mac_jdk.html#A1096903 and https://www.java.com/en/download/help/mac_uninstall_java.xml) and install JDK 1.8 (http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html).

5. Enable the developer mode for your android device. (https://www.androidcentral.com/how-enable-developer-settings-android-42)

6. Go to the project folder and run `cordova run android —device`. Install corresponding missing packages if you encounter any error messages.


