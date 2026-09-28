# 2.App - Android Mobile Application

![Android](https://img.shields.io/badge/Platform-Android-green?style=flat-square&logo=android)
![Java](https://img.shields.io/badge/Language-Java-orange?style=flat-square&logo=java)
![Min SDK](https://img.shields.io/badge/Min%20SDK-24%20(Android%207.0)-blue?style=flat-square)
![Target SDK](https://img.shields.io/badge/Target%20SDK-37-blue?style=flat-square)
![Build](https://img.shields.io/badge/Gradle-Kotlin%20DSL-0640FF?style=flat-square&logo=gradle)

A native Android mobile application built with **Java** and **AndroidX Material Components**. This project demonstrates essential Android UI components, responsive layouts using `ConstraintLayout`, and modern Android design practices such as **Edge-to-Edge** window display.

---

## 📱 Features

- **Modern Layout Design**: Powered by `ConstraintLayout` for flexible and responsive screen positioning.
- **Edge-to-Edge Support**: Leverages `WindowInsetsCompat` and `ViewCompat` for seamless display around system bars.
- **Interactive UI Elements**:
  - `RadioGroup` & `RadioButton` (Gender selection)
  - `CheckBox` (Newsletter subscription)
  - `Button` (Login action)
  - `FloatingActionButton` (Quick action button)
  - Styled `TextView` headings

---

## 🛠 Tech Stack

- **Language**: Java (Java 11)
- **Framework**: Android SDK (Min API 24 / Target API 37)
- **UI Components**: 
  - AndroidX AppCompat
  - Google Material Design Components
  - ConstraintLayout
- **Build System**: Gradle with Kotlin DSL (`build.gradle.kts`) & Version Catalog (`libs.versions.toml`)

---

## 📁 Project Structure

```text
[2App/](file:///C:/Users/e19/AndroidStudioProjects/2App/)
├── [app/](file:///C:/Users/e19/AndroidStudioProjects/2App/app/)
│   ├── [build.gradle.kts](file:///C:/Users/e19/AndroidStudioProjects/2App/app/build.gradle.kts)             # App-level build configuration
│   └── [src/](file:///C:/Users/e19/AndroidStudioProjects/2App/app/src/)
│       └── [main/](file:///C:/Users/e19/AndroidStudioProjects/2App/app/src/main/)
│           ├── [java/com/example/a2app/](file:///C:/Users/e19/AndroidStudioProjects/2App/app/src/test/java/com/example/a2app/)
│           │   └── [MainActivity.java](file:///C:/Users/e19/AndroidStudioProjects/2App/app/src/main/java/com/example/a2app/MainActivity.java) # Main Activity source code
│           ├── [res/](file:///C:/Users/e19/AndroidStudioProjects/2App/app/src/main/res/)
│           │   ├── [layout/](file:///C:/Users/e19/AndroidStudioProjects/2App/app/src/main/res/layout/)
│           │   │   └── [activity_main.xml](file:///C:/Users/e19/AndroidStudioProjects/2App/app/src/main/res/layout/activity_main.xml) # Main UI Layout
│           │   ├── [values/](file:///C:/Users/e19/AndroidStudioProjects/2App/app/src/main/res/values/)          # Strings, colors, styles
│           │   └── [drawable/](file:///C:/Users/e19/AndroidStudioProjects/2App/app/src/main/res/drawable/)        # Vector drawables & icons
│           └── [AndroidManifest.xml](file:///C:/Users/e19/AndroidStudioProjects/2App/app/src/main/AndroidManifest.xml)  # Application Manifest
├── [gradle/](file:///C:/Users/e19/AndroidStudioProjects/2App/gradle/)
│   └── [libs.versions.toml](file:///C:/Users/e19/AndroidStudioProjects/2App/gradle/libs.versions.toml)           # Dependency version catalog
├── [build.gradle.kts](file:///C:/Users/e19/AndroidStudioProjects/2App/app/build.gradle.kts)                 # Root build configuration
└── [README.md](file:///C:/Users/e19/AndroidStudioProjects/2App/README.md)                        # Project documentation
