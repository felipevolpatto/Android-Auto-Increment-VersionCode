# Android-Auto-Increment-VersionCode
This project simply bumps the version code on each build on build.gradle

It simply reads the versionCode from an external file and depending if it is the release flavor or the debug flavor increase the versionCode of you Android application.

## Installation

Just copy and past on your app folder

## Usage

By default, bump version is disabled. To enable it, just change `IS_RELEASE` on `version.properties`

```sh
IS_RELEASE=false
```

## License

Android-AutoIncrement-VersionCode is released under the [MIT License](http://www.opensource.org/licenses/MIT).
