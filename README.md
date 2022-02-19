# AutoUssd

![](https://img.shields.io/badge/version-2.0.0-blue) ![](https://img.shields.io/badge/platform-android-brightgreen) ![](https://img.shields.io/badge/min%20sdk%20version-API%2023-orange)

[AutoUssd](https://autoussd.com) is a powerful USSD automation SDK for Android which allows you to build Android applications on top of USSD services. Find out more on our [website](https://autoussd.com).

## Requirements

- Your app must must target a `minSdkVersion` of **23** or higher

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
  implementation 'com.autoussd:autoussd-sdk:1.2.1';
}
```

3. Sync project with Gradle Files

## Usage

Click [here](https://autoussd.com/docs) to visit our beginner-friendly [guide](https://autoussd.com/docs) to get started with AutoUssd.