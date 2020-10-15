# Cordova-App "Hallo Name" mit Bootstrap #

This repository contains the [Cordova](https://cordova.apache.org/) project for a very simple mobile app based on the UI/CSS framework [Bootstrap](https://getbootstrap.com/),
that can be compiled to an Android app and also to an iOS app (for the latter one a MacOS computer is needed).

The actual code of the app is contained in folder [www](www/).

<br>

----
## Build the app ##

Prerequisites for building the app:

* [Node.js with NPM](https://nodejs.org/en/download/) is installed.

* Java is installed and environment variable `JAVA_HOME` is defined.

* Android SDK is installed (e.g. as part of [Android Studio](https://developer.android.com/studio)) and environment variable `ANDROID_SDK_ROOT` is defined.

* Check if Cordova is installed: `cordova --version`.
  If Cordova is not installed, then use the following command to install it: `npm install -g cordova`

<br>

To build the app for Android you have to open a command prompt/shell in the cloned repository folder and enter the following commands:

1. `npm install`

2. Add Android as target platform: `cordova platform add android`

3. Build the app: `cordova build android`

4: Run it in emulator (optional): `cordova run android`

<br>

----
## License ##

See the [LICENSE file](LICENSE.md) for license rights and limitations (BSD 3-Clause License) for the files in this repository.

The repository contains some files from *Bootstrap*, which is licensed under the terms of the [MIT License](https://getbootstrap.com/docs/4.4/about/license/) and is copyrighted by Twitter.
The repository also contains *jQuery*, which is also licensed under the terms of the [MIT License](https://jquery.org/license/).

<br>
