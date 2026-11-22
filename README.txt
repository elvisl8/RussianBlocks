Russian Blocks - Android project (WebView wrapper around the game)

Build the APK:
1. Install Android Studio, choose File > Open, and select this folder.
2. Let Gradle sync (it downloads the SDK pieces it needs).
3. Plug in a phone with USB debugging, or start an emulator, then press Run.
4. For a shareable file: Build > Build Bundle(s) / APK(s) > Build APK(s).

The game lives in app/src/main/assets/index.html. Edit it and rebuild to change the game.
Fonts load from Google Fonts when online; offline it falls back to system fonts.
