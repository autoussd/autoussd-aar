# AutoUssd

![](https://img.shields.io/badge/version-2.0.0-blue) ![](https://img.shields.io/badge/platform-android-brightgreen) ![](https://img.shields.io/badge/min%20sdk%20version-API%2023-orange) ![](https://img.shields.io/badge/compile%20sdk%20version-API%2031-orange)

[AutoUssd](https://autoussd.com) is a powerful automation SDK for Android which allows you to build Android applications on top of **[USSD](https://www.techtarget.com/searchnetworking/definition/USSD)** services. Find out more on our [website](https://autoussd.com).

## Requirements

- Your app must must target a `minSdkVersion` of **23** or higher
- Your app must have a `compileSdkVersion` of **31**

## Installation

1. Add the Maven repository to your **project-level** `build.gradle`

```groovy
allProjects {
  repositories {
    ...
    maven { url 'https://raw.github.com/autoussd/autoussd-aar/master' };
  }
}
```

2. Add the SDK dependency to your **app-level** `build.gradle`

```groovy
dependencies {
  ...
  implementation 'com.autoussd:autoussd-sdk:2.0.2';
}
```

3. Sync project with Gradle Files

## Usage

Click [here](https://autoussd.com/docs) to visit our beginner-friendly [guide](https://autoussd.com/docs) to get started with AutoUssd.