# Explore - Flutter/FireStore/Google-Map by Akash Divya

This is a Flutter App with Firebase's Cloud FireStore Database and Google Map.
This app represents that Customizable Beautiful UI can be implemented with the Best Performance possible.

![Banner Image](https://github.com/AkashDivya/Explore-Flutter-FireStore/blob/master/images/Banner.jpg)

# Things implemented in this App

This was my first Flutter App. My intentions were to implement as many things as I can so that I can learn those things.
This App contains the implementation of the followings:
  - Firebase's Cloud FireStore
  - Firebase's Cloud Storage
  - Custom Firebase Text by Text Search
  - Official Google Map
  - BLoC Pattern/Architecture
  - StreamBuilder
  - StreamSubscription
  - Dynamic Theme
  - Internet Connectivity Status
  - Customizing Status Bar & Navigation Tab
  - PageView
  - Custom Icon & Splash Screen
  - Various Material Components

# How to get this Repo and run it on your System

I kept the code as original as possible with prober Commented Guides for anyone to understand and implement. Still you need to follow these steps.
  - First get Flutter and all necessary SDK/Plugins installed. Full guide here [Flutter: Get Started](https://flutter.dev/docs/get-started/install)
  - Now create a new Flutter App, named as **'exploreapp'** with AndroidX Compatibility.
    ```
    flutter create --androidx exploreapp
    ```
  - Now download this [Repo](https://codeload.github.com/AkashDivya/Explore-Flutter-FireStore/zip/master)
  - Extract the Repo into your newly created **exploreapp** and replace the required files.
  - Now go to [Firebase](https://console.firebase.google.com/) and start a new project. Follow these [guidelines](https://firebase.google.com/docs/android/setup) here and paste the file **google-services.json** from there into your project. (We are doing this just for Android Platform)
    
    _'yourDirectory'\exploreapp\android\app_
    
  - Now Populate your FireStore Database like examples below:
  
    ![Firebase_Example_01](https://github.com/AkashDivya/Explore-Flutter-FireStore/blob/master/images/Firestore%20Database%20(1).png)
    ![Firebase_Example_02](https://github.com/AkashDivya/Explore-Flutter-FireStore/blob/master/images/Firestore%20Database%20(2).png)
    ![Firebase_Example_03](https://github.com/AkashDivya/Explore-Flutter-FireStore/blob/master/images/Firestore%20Database%20(3).png)
    ![Firebase_Example_04](https://github.com/AkashDivya/Explore-Flutter-FireStore/blob/master/images/Firestore%20Database%20(4).png)
  - Now go to [Google API](https://console.developers.google.com/) and Enable **Maps SDK for Android** and get thi API Key.
  - Paste this API Key in the pecific area where I mentioned **"Your Map API Key here"** in **AndroidManifest.xml** file which can be found in _'yourDirectory'\exploreapp\android\app\src\main\_ like written below:
    ```
    <application>
    ...
    <meta-data android:name="com.google.android.geo.API_KEY"
               android:value="Your Map API Key here"/>
    ```
  - Now you can Finally run VS-Code or Android Studio whichever you prefer and get the flutter packages and just run the App.
  
# Download the APK

Check the apk files included in this Repo. Install them on your device to test it.

  [Download arm64 APK](https://raw.githubusercontent.com/AkashDivya/Explore-Flutter-FireStore/master/release%20builds/app-arm64-v8a-release.apk)
  
  [Download armeabi APK](https://raw.githubusercontent.com/AkashDivya/Explore-Flutter-FireStore/master/release%20builds/app-armeabi-v7a-release.apk)


# App Demonstration Video

  [![Explore - Flutter App Showcase](https://img.youtube.com/vi/Mb-b4zVODmk/0.jpg)](https://www.youtube.com/watch?v=Mb-b4zVODmk)
  
  [Watch Video on Youtube](https://www.youtube.com/watch?v=Mb-b4zVODmk)
  
# Local Assets & Json Data Variant

If you are wondering how you can do it with local assets and json data you can visit this [Repo](https://github.com/AkashDivya/Explore-Flutter-LocalAssets-JSON)

# About Me

I'm a veteran Designer/Animator with **10+ years** of experience. I always hated the excuses Developers gave me when they fail to implement my Design. One day, when I found about Flutter I said no more & started learning it.
This is my first App which I developed, and the design i took from dribbble [Link](https://dribbble.com/shots/6237475-Travel-Stories-Concept) and I also designed the parts which were not there.

# My Links

**[Facebook](https://www.facebook.com/BadassDeveloperDesignerClub)**

**[YouTube](https://www.youtube.com/channel/UCo7mhMbZXaNgpyT7gM6mWDQ)**

**[Dribbble](https://www.dribbble.com/akashdivya)**

**[Behance](https://www.behance.net/akashdivya)**

**Email: akash.apd@gmail.com**

**Now go out there and do what you Love.**
