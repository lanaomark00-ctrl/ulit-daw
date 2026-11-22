# Smart KTV Piano 4K (Android)

A WebView wrapper around the app in `app/src/main/assets/index.html`. It controls a simulated karaoke box.

## Build the APK
**Android Studio:** File > Open this folder, wait for Gradle sync, then Build > Build APK(s).
The file is `app/build/outputs/apk/debug/app-debug.apk`.

**GitHub:** push this folder to a repo. The "Build APK" workflow (Actions tab) uploads `app-debug.apk` as an artifact.

**Command line** (Android SDK installed; the Gradle wrapper is included): `./gradlew assembleDebug`

Install the debug APK on a phone or Android TV; allow "install unknown apps" if asked.
