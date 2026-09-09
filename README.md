# Panda Pop Rush

Android APK build setup for the existing `panda-pop-rush.html` web app.

## APK build

GitHub Actions automatically builds a debug APK whenever `main` is updated.

The workflow expects the original app file at the repository root:

`panda-pop-rush.html`

It copies that file into the Android WebView assets and builds:

`app/build/outputs/apk/debug/app-debug.apk`
