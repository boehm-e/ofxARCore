# ofxARCore
Experimental addon for openFrameworks to use [ARCore](https://developers.google.com/ar) on Android devices.

![preview](preview.gif)

## About
This addon is based on the work of [HalfdanJ](https://github.com/HalfdanJ/).
This is not an official Google product.

## Developer guide
To use the addon, you need the development branch of openFrameworks from [github](http://github.com/openFrameworks/openFrameworks).  Follow the [Android Studio guide](https://github.com/openframeworks/openFrameworks/blob/master/docs/android_studio.md) to learn how to get started with openFrameworks and Android.

To add the addon, add `ofxARCore` to `addons.make` in your project, or through the project generator. Additionally you will need to add the following two lines to the end of `settings.gradle` of your project:

To see basic usage of the addon, see the [example code](exampleBasic/src/ofApp.cpp)

## Examples
### [Basic example](exampleBasic/)
Shows how to use the addon in the most basic way, just rendering a grid centered around origin.

### [Drawing example](exampleDrawing/)
A simple demo that lets you draw in the air.

The app calculates the world coordinates from touch events on the screen, and draws a continuous white line through the air. Read more on [AR Experiments site](https://experiments.withgoogle.com/ar).

There is also a never version ported to Java available here: [github.com/googlecreativelab/ar-drawing-java](https://github.com/googlecreativelab/ar-drawing-java)
