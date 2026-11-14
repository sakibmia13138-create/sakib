# Aim Engine Android project

This is a native Android WebView wrapper around the Aim Engine 1.0 web app.
It opens directly to the app — no user login or registration screen is included.

## Build an APK
1. Open this folder in Android Studio (Giraffe or newer).
2. Allow Gradle sync and install Android SDK Platform 35 if prompted.
3. Select Build > Build Bundle(s) / APK(s) > Build APK(s).
4. Android Studio will show the generated APK location, normally `app/build/outputs/apk/debug/app-debug.apk`.

## Notes
- This is a wrapper around the locally bundled web app and assets.
- Profile data and notes remain local to the device/browser storage.
- Demo automation controls are UI demonstrations; they do not control games or other apps.
- This is not the original Fine Engine binary and does not reproduce its protected server-side features.
