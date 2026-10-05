# MAD Practical – Frame by Frame Animation & Twin Animation

## AIM

Create an Android application to demonstrate **Frame by Frame Animation** and a **Splash Screen** using **Twin Animation**.

## Features

* Frame by Frame Animation using `AnimationDrawable`
* Splash Screen
* Twin Animation
* Scale Animation
* Translate Animation
* Rotate Animation
* Alpha Animation
* Animation Set using `<set>`
* Animation List using `<animation-list>`
* Edge-to-Edge Content Display
* Immersive Mode
* Animation Listener
* Activity Transition Animation
* SVG to Android Vector Drawable conversion

## Concepts Used

* `ImageView`
* `AnimationDrawable`
* `AnimationUtils`
* `loadAnimation()`
* `setAnimationListener()`
* `onWindowFocusChanged()`
* `overridePendingTransition()`
* `finish()`
* `<animation-list>`
* `<set>`
* `<scale>`
* `<translate>`
* `<rotate>`
* `<alpha>`
* `startOffset`
* `duration`
* `res/anim` folder

## Splash Screen

The Splash Screen uses a **radial gradient rectangle** with:

* Shape: Rectangle
* Gradient: Radial
* Center X: `0.9`
* Center Y: `0.9`
* Radius: `1500`
* Start Color: Pink
* End Color: Blue

## Application Flow

```text
SplashActivity
      ↓
Twin Animation
      ↓
Animation Completed
      ↓
MainActivity
      ↓
Frame by Frame Animation
```

## Image Sequences

### Alarm

[Download/View Alarm Image Sequence](https://drive.google.com/embeddedfolderview?authuser=0&id=1CtM_4SRIlgOLw9e09Bn-vOfkU4FoIO10#list)

### Heart

[Download/View Heart Image Sequence](https://drive.google.com/embeddedfolderview?authuser=0&id=1_t9Grem_r54NpP7FSI8Ov-uyfDmputK1#list)

### UVPCE Logo

[Download/View UVPCE Logo Image Sequence](https://drive.google.com/embeddedfolderview?authuser=0&id=1_xSJ2lIvX6cptO8Nk0_d_nFZirZ-Pklx#list)

## Project Structure

```text
app/
└── src/
    └── main/
        ├── java/
        │   └── MainActivity.kt
        │   └── SplashActivity.kt
        │
        └── res/
            ├── anim/
            │   ├── scale.xml
            │   ├── translate.xml
            │   ├── rotate.xml
            │   ├── alpha.xml
            │   └── twin_animation.xml
            │
            ├── drawable/
            │   ├── splash_background.xml
            │   └── animation_list.xml
            │
            └── layout/
                ├── activity_main.xml
                └── activity_splash.xml
```

## Technologies

* **Language:** Kotlin
* **Platform:** Android
* **UI:** XML
* **Animation:** Android Animation Framework

## Learning Outcome

This practical demonstrates how to implement **frame-by-frame animation, twin animation, splash screens, XML animations, activity transitions, and edge-to-edge display** in an Android application.

