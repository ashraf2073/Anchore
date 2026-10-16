# Anchor
Offline-first grounding app. No network code, no tracking; everything stays on the device.

## Get the APK
**Easiest:** push this folder to a GitHub repo (branch `main`) > Actions > "Build APK" > download the `Anchor-APK` artifact. Install it on Android (allow "install unknown apps").
**Locally:** install Node 22, JDK 21, Android SDK, then `npm install && npm run apk`. APK: `android/app/build/outputs/apk/debug/app-debug.apk`.
**Quick preview:** host the files over HTTPS and use "Add to Home Screen".

The APK is debug-signed (fine for sideloading). Sign a release build for Play Store.
