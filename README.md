# App Store Connect

## How to Upload yout App Mobile to the Apple Store


Need to have:

- [x] iOS equipment
- [x] Apple Developer Account 
- [x] Xcode 10
- [x] Ionic Framework 4
- [x] Steadfastness
- [x] Time... of course



In this repo I describe my experience as a mobile developer, and what are the main obstacles that I had to overcome, when uploading an app to the Apple Store. I also describe the essential aspects of Xcode in its version 10.


Let's suppose that you have already made your Mobile App in __Ionic Framework__ or some other similar cross-platform framework.

Arriving at this instance, you may want to generate the corresponding compilations for Google Play Store and Mac Store.

In this post I will focus only on the __Mac Store__, because the process for google is very simple.

Let's do it

## - Generating the compilation for iOS

1 - Once we have the Ionic project properly configured and working, we must prepare the compilation for IOS through the following command:    

```
ionic cordova prepare ios --verbose
```

The command above will generate the project for ios platform, and ready to be opened with __XCODE__    

## - Editing the Project with XCode   

At this point we should no longer have to use Ionic, unless we need to make a significant modification to our App.    

  *  First we open Xcode and we will open a file "File -> Open"     
  *  Then find the file with extension .xcodeproj that is located in this route:    
 
 ```
 /name_of_your_app/platforms/ios/name_of_your_app.xcodeproj
 ```   
 
 
Once the project is open, I will briefly describe each section of Xcode, and how to identify and familiarize ourselves with the work area:


![Xcode Capture Image](https://raw.githubusercontent.com/aledc7/AppStoreConnect/master/assets/Xcode_general.png "Xcode Capture Image")
 
 
 ### Each number is described
 
1. Project Navegator.
   This small square will be the one that we will have selected most of the time.
   
2. Genral Tab.
   This tab Contain the principal info of your App, must be selected to edit the info that I will describe below.

3.  
  * Display Name:  Is the name of your App
  * Bundle Identifier: will be the name assigned in the Apple Store, and will never change throughout the development.
  * Version:  It will be the version of your app, and it should be increased with each change you make.
  * Build: Is similar to Version.

4. Signing
  * Automatically Manage Signing  (if it is enabled everything happens easier)
5. Team
  * The TEAM must be previously defined from the Apple developer account.
6. Device Orientation
  * Depending on the need, it may be convenient to disable the horizontal mode (landscape) this will prevent the appearance of your app from breaking.
     
 
 



  
