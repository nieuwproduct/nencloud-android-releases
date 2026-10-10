# NenCloud Android

This repository publishes the NenCloud Android app only. It does not contain source code.

- Download page: https://nieuwproduct.github.io/nencloud-android-releases/
- Latest APK: https://github.com/nieuwproduct/nencloud-android-releases/releases/download/android-v1.2.0/nencloud-android.apk
- Version: 1.2.0 (versionCode 10200)

The download page is `index.html`. The app reads `version.json` when it checks for updates.
Pushing an `android-v*` tag runs `.github/workflows/release.yml`, which attaches the APK to the GitHub Release.
