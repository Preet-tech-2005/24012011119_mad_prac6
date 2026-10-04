# Practical-6: Frame-by-Frame & Twin Animation

## 👤 Author

**Name:** Preet Patel
**Enrollment No.:** 24012011119

---

## 🎯 Aim

To develop an Android application that demonstrates **Frame-by-Frame Animation** and **Twin Animation** using Android's built-in animation features.

---

## 📖 About the Practical

This practical focuses on implementing different types of animations in an Android application and understanding how animation components work together.

### 1. Frame-by-Frame Animation

Frame-by-frame animation creates motion by displaying a collection of images sequentially. Each image is shown for a specified duration, producing the appearance of continuous movement.

In this application, frame animation is implemented for:

* **UVPCE Logo** — 8 individual frames
* **Alarm Animation** — 10 frames
* **Heart Animation** — 5 frames

### 2. Twin Animation

Twin animation is used to combine different animation operations and apply them together to a single view.

On the splash screen, the UVPCE logo is animated using multiple transformations before the application proceeds to the main alarm screen.

---

## 📱 Application Screens

The application contains two primary screens:

### Splash Screen

The splash screen presents the UVPCE/Ganpat University logo through an 8-frame animation.

A blue and pink gradient background is provided to enhance the appearance of the splash screen. The logo images are displayed sequentially to produce the frame animation effect.

### Alarm Screen

The main screen provides the following functionality:

* Animated alarm clock
* Animated heart icon
* Display of the current time
* Create Alarm option
* Cancel Alarm option
* Time Picker for selecting alarm time
* Alarm scheduling and cancellation
* Light and Dark theme support

---

## 🛠️ Concepts & Components Used

* `ImageView`
* `AnimationDrawable` for frame-by-frame image animation
* `AnimationUtils` for loading animation resources
* `Animation.AnimationListener` for handling animation start, completion, and repetition
* `onWindowFocusChanged()` to start the frame animation after the view becomes available
* `<animation-list>` for defining a sequence of drawable frames
* `android:oneshot` to control whether an animation runs once or continuously
* `<set>` for combining multiple animation operations
* `<translate>`, `<rotate>`, and `<scale>` for creating twin animation effects
* `enableEdgeToEdge()` for edge-to-edge screen display
* `WindowInsetsCompat` for managing system bar spacing
* `<gradient>` inside `<shape>` for creating the splash screen background
* `ConstraintLayout` for designing the application interfaces
* `MaterialCardView` for displaying the information section
* `Intent` for moving from `SplashActivity` to `MainActivity`

---

## 📱 Output

### 🎬 Demo Video

[<video src="https://github.com/Preet-tech-2005/24012011119_mad_prac6/blob/master/Screenrecording/Screen_recording_20261004_2121041.webm" controls width="320"></video>](https://github.com/user-attachments/assets/e102655d-bcdd-4e6a-afd9-5131dc12629b)

---

### 🖼️ Screenshots

#### Splash Screen — Frame Animation & Twin Animation

<table>
  <tr>
    <td width="33%"><img src="Screenshots/Layout - 1.png" width="100%"/></td>
    <td width="33%"><img src="Screenshots/Layout - 2.png" width="100%"/></td>
    <td width="33%"><img src="Screenshots/Layout - 3.png" width="100%"/></td>
  </tr>
  <tr>
    <td align="center">Initial Animation</td>
    <td align="center">Rotation and Scaling</td>
    <td align="center">Completed Animation</td>
  </tr>
</table>

#### Main Screen — Frame Animation

<table>
  <tr>
    <td width="33%"><img src="Screenshots/Layout - 4.png" width="100%"/></td>
    <td width="33%"><img src="Screenshots/Layout - 5.png" width="100%"/></td>
  </tr>
  <tr>
    <td align="center">Alarm Animation - Frame 1</td>
    <td align="center">Alarm Animation - Frame 2</td>
  </tr>
</table>

---

## 🔗 Source Code

**GitHub Repository:** 
