This project demonstrates how to combine Java application with native C/C++ code for OpenGL rendering on Android 2.3 and newer.  The solution gives full control of the rendering for the native code while still allowing the convenience of using Java for calling Android APIs.

The example uses pthreads, OpenGL and EGL API in the native code.  `GLSurfaceView` and `GLSurfaceView.Renderer` Java classes are not used.  The application is still running standard Java activity and not the `NativeActivity`.

[Click here](http://code.google.com/p/android-native-egl-example/source/browse/) to browse  or download the source code as zip file.

Or use [Mercurial](http://mercurial.selenic.com/) to download the source:
```
hg clone https://code.google.com/p/android-native-egl-example/
```

If you are using Android Studio 0.9 or later [click here](https://code.google.com/p/android-native-egl-example/source/browse/?repo=gradle) for a version of the example code which uses Gradle for compiling.

![http://i.imgur.com/qTfiE.png](http://i.imgur.com/qTfiE.png)