
<p align="center">
  <h1 align="center">Introslider | Neumorphism</h1>
  
  Android Application to display intro slider which attracts and helps the user to know about the application using JAVA programming language.
  Launch Frist time using SharedPreferences.
  

<div align="center">

<a href="https://t.me/banrossyn" target="_blank"><img src="https://img.shields.io/badge/Telegram-%40banrossyn-28a8ea"></a>
<a href="https://wa.me/+919694260426/" target="_blank"><img src="https://img.shields.io/badge/whatsapp-%40+919694260426-28a8ea"></a>
<a href="https://www.linkedin.com/in/banrossyn/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-banrossyn-informational"></a>
<a href="mailto:banrossyn@gmail.com"><img src="https://img.shields.io/badge/Email-banrossyn%40gmail.com-blue"></a>

</div>


![IntroSlider ](https://user-images.githubusercontent.com/97843190/173628294-7a1ed406-badf-4c8f-bca1-4161e11a5580.jpg)

# Build Neumorphism designs in Android.

Dependency

Add this in your root `settings.gradle` file (**not** your module `build.gradle` file):

```gradle

dependencyResolutionManagement {
    repositoriesMode.set(RepositoriesMode.PREFER_SETTINGS)
    repositories {
    ....
        maven { url "https://jitpack.io" }
        ...
    }
}
```

Then, add the library to your module `build.gradle`
```gradle
dependencies {
    implementation 'com.github.fornewid:neumorphism:{latest_version}'
}
```
  <p align="center">
 
<img height="200" src='https://github.com/fornewid/Neumorphism/blob/main/art/preview.png'/>
</p>
<p align="center">
<a href="https://opensource.org/licenses/Apache-2.0"><img src="https://img.shields.io/badge/License-Apache%202.0-blue.svg"/></a>
<a href='https://developer.android.com'><img src='http://img.shields.io/badge/platform-android-green.svg'/></a>
<a href='https://jitpack.io/#fornewid/neumorphism'><img src='https://jitpack.io/v/fornewid/neumorphism.svg'/></a>
</p>

## Features
- Draw a shadow background on widgets for Neumorphism.
  Supported on the following widgets:
  - ViewGroup: CardView
  - View: Button, FloatingActionButton, ImageView
- Draw a text shadow on TextView for Neumorphism.



