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

## 1 - Generating the compilation for iOS

1 - Once we have the Ionic project properly configured and working, we must prepare the compilation for IOS through the following command:    

```
ionic cordova prepare ios --verbose
```

The command above will generate the project for ios platform, and ready to be opened with __XCODE__    

## 2 - Editing the Project with XCode   

At this point we should no longer have to use Ionic, unless we need to make a significant modification to our App.    

 2.1 First we open Xcode and we will open a file "File -> Open"     
 2.2 Then find the file with extension .xcodeproj that is located in this route:    
 
 ```
 /name_of_your_app/platforms/ios/name_of_your_app.xcodeproj
 ```   
 
 
Once the project is open, I will briefly describe each section of Xcode, and how to identify and familiarize ourselves with the work area.    
 
 
 
 
 



  
