# WiFind

An app that collects WiFi data.

[![Stories in Ready](https://badge.waffle.io/wifimapping/app.png?label=ready&title=Ready)](http://waffle.io/wifimapping/app)

# Setup

1. Install [Nodejs](nodejs.org)
2. Install phonegap, cordova, ionic and bower globally

      npm install -g phonegap cordova ionic bower

3. Setup the app's platforms and plugins:

      ionic state restore

4. Install bower packages:

      bower install

# Testing

Test the app locally with:

    phonegap serve

None of the native phone features will work, but the app should load in a browser and not have javascript errors.

To test it on a phone you can build an APK and then install it. Build it with:

    phonegap remote build android
