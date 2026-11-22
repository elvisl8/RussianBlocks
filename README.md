# Russian Blocks — Android

A WebView wrapper around a self-contained HTML5 block game
(`app/src/main/assets/index.html`). No third-party dependencies.

- Package: `com.example.russianblocks`
- minSdk 24 (Android 7.0+), targetSdk / compileSdk 34
- AGP 8.5.2, Gradle 8.7, Java 17

## Build on GitHub (no local SDK needed)

Push this repo to GitHub and the **Build Russian Blocks APK** workflow
(Actions) compiles a debug APK on every push to `main`. Download it from
the run's Artifacts section (`RussianBlocks-debug`). The workflow caches
one debug keystore, so later builds install over earlier ones without a
signature conflict.

Run it manually any time from the Actions tab (`workflow_dispatch`).

## Build locally

Open the folder in Android Studio, let Gradle sync, then Run — or
Build > Build APK(s) for a shareable file. See `README.txt` for the
original notes.

## Changing the game

Edit `app/src/main/assets/index.html` and rebuild. Fonts load from Google
Fonts when online; offline it falls back to system fonts.
