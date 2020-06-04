# android-host-demo

## settings.gradle 需要更改flutter module项目的路径

flutter module项目见 [flutter module](https://github.com/XiaoWangXueBianCheng/fluttermodule-demo.git)

集成方式见[flutter add-to-app](https://flutter.cn/docs/development/add-to-app/android/project-setup)

## 重现 bug `E/flutter: [ERROR:flutter/shell/gpu/gpu_surface_gl.cc(70)] Failed to setup Skia Gr context.`
device: 小米 pad(MI PAD 2)
reproduce:add abiFilter in app/build.gradle `abiFilter "armeabi-v7a"`

## 这是一个android support项目集成了flutter module

flutter module 版本

[✓] Flutter (Channel v1.12.13-hotfixes, v1.12.13+hotfix.9, on Mac OS X 10.15.3 19D76, locale zh-Hans-CN)
    • Flutter version 1.12.13+hotfix.9 at ～/development/flutter
    • Framework revision f139b11009 (9 weeks ago), 2020-03-30 13:57:30 -0700
    • Engine revision af51afceb8
    • Dart version 2.7.2


[✓] Android toolchain - develop for Android devices (Android SDK version 29.0.3)
    • Android SDK at ～/Library/Android/sdk
    • Android NDK location not configured (optional; useful for native profiling support)
    • Platform android-29, build-tools 29.0.3
    • Java binary at: /Applications/Android Studio.app/Contents/jre/jdk/Contents/Home/bin/java
    • Java version OpenJDK Runtime Environment (build 1.8.0_212-release-1586-b4-5784211)
    • All Android licenses accepted.

[✓] Xcode - develop for iOS and macOS (Xcode 11.4)
    • Xcode at /Applications/Xcode-beta.app/Contents/Developer
    • Xcode 11.4, Build version 11N111s
    • CocoaPods version 1.9.1

[✓] Android Studio (version 3.6)
    • Android Studio at /Applications/Android Studio.app/Contents
    • Flutter plugin version 45.1.1
    • Dart plugin version 192.7761
    • Java version OpenJDK Runtime Environment (build 1.8.0_212-release-1586-b4-5784211)

[✓] Android Studio (version 3.6)
    • Android Studio at /Applications/Android Studio 2.app/Contents
    • Flutter plugin version 45.1.1
    • Dart plugin version 192.7761
    • Java version OpenJDK Runtime Environment (build 1.8.0_212-release-1586-b4-5784211)

[✓] Android Studio (version 3.5)
    • Android Studio at /Applications/Android Studio 3.app/Contents
    • Flutter plugin version 43.0.1
    • Dart plugin version 191.8593
    • Java version OpenJDK Runtime Environment (build 1.8.0_202-release-1483-b49-5587405)

[✓] VS Code (version 1.45.1)
    • VS Code at /Applications/Visual Studio Code.app/Contents
    • Flutter extension version 3.11.0

[✓] Connected device (1 available)
    • MI PAD 2 • A3P4ED914703 • android-x64 • Android 5.1 (API 22)