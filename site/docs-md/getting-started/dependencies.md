# Capacitor Required Dependencies

## iOS Development

For building iOS apps, Capacitor requires a Mac with Xcode 9 or above. Soon, you'll be able to use [Ionic Pro](http://ionicframework.com/pro) to build for iOS even if you're on Windows.

As a rule, the latest version of Capacitor always supports the last two iOS versions. For example, iOS 11 and iOS 10. For support for older versions of iOS, use an older version of Capacitor (if available).

## Android Development

Android development requires the Android SDK installed with [Android Studio](https://developer.android.com/studio/index.html). Technically, Android Studio isn't required as you can build and run apps using only the Android CLI tools, but it will make building and running your app much easier so we strongly recommend using it.

Android version support for Capacitor is more complex than iOS. Currently, we are targeting API level 19 or greater, meaning Android 4.4 (KitKat) or above.

As of January 2018, 4.4 or greater represents over 88% of the Android market, and this percentage is growing quickly.

Our goal with Android support will be to target at least 85% of the market.

## Progressive Web App Development

For building Progressive Web Apps, simply run and deploy your web assets folder to the web! Depending on your project set up, that folder may be `public/` or `www/`. 

If you're using a framework like Ionic, consult the appropriate documentation for specific details relating to deploying PWAs in that framework.

## Electron Development

*Coming soon.* Electron support isn't ready just yet.