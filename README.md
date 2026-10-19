# PIXEL BEATS 🎵 — Android APK build

This repository layout wraps the PIXEL BEATS web player in an Android app using Capacitor.

## Build the APK with GitHub Actions
1. Upload/commit these files to the root of your GitHub repository, including `.github/workflows/build-apk.yml`.
2. Open the repository's **Actions** tab.
3. Select **Build Android APK** and click **Run workflow** (or push a commit to `main`/`master`).
4. When the workflow completes, open the run and download the `pixel-beats-debug-apk` artifact.
5. Extract the ZIP; it contains `app-debug.apk`. Transfer it to your Android phone and install it.

This creates a debug APK for sideloading/testing, not a Play Store-signed release.
Background audio and lock-screen controls depend on Android WebView and device behavior; test these on the target device.
