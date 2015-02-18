Android Custom Toggle Buttons
=============================

[Visit the GISi Blog](http://gisinc.com/talk/creating-reusable-custom-toggle-button-android-applications/) for a tutorial covering the code in this repo

Often during the creation of an Android application, a developer will need to create a settings page. This allows the app's user to change settings for the application that will persist to the next session, such as "enable my location" or "show map markers". Each setting is in effect an on/off switch. The Android SDK comes with a couple widgets to accomplish this task: ToggleButton and Switch (new to Ice Cream Sandwich 4.0). These controls work fine for setting an on/off state within the application. But... they're pretty lame. As you move beyond the beginner stages in Android development, you'll want to learn how to create your own controls with your own look and feel. Android's built in componentized model allows a developer to create Custom Components that you can use to construct your UI. For our purposes a Compound Control will do the job. According to the Android documentation, Compound Controls allow you to "to put together a reusable component that consists of a group of existing controls". Let's take a look at how we can create a better-looking toggle button.

The toggle button will consist of a black oval containing a circle. The circle's position represents the current setting: left for "off", right for "on". When the toggle button is pressed, the circle will move to the right and the containing oval will animate to green.

BONUS: this control is directly tied to Android's SharedPreferences, so your setting will persist to the device

!["Custom Toggle Button"](https://raw.githubusercontent.com/gisinc/android-toggle-button/master/togglebutton.gif)

### Requirements

Android Studio

### Usage

Clone the repo, open the project file AndroidToggleButton.iml

### ToDo

Turn this into a reusable package, add explosions

### License

The MIT License (MIT)

Copyright (c) 2014 Geographic Information Services, Inc. (GISi)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
