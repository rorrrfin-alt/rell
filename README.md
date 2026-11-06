# Jaccksallas Admin Dashboard

A minimal Android Studio project for a transparent, local-only device diagnostics dashboard.

## Included
- Device manufacturer/model and Android version
- Battery percentage
- Internal storage usage
- Current network transport
- Dark dashboard UI with red accents

## Privacy and scope
This build performs local reads only. It does not include RAT functionality, hidden persistence,
remote shell, file exfiltration, camera/microphone capture, or background command execution.
No data is transmitted to any server.

## Build
1. Install Android Studio (Hedgehog or newer) and Android SDK Platform 35.
2. Open this folder in Android Studio.
3. Allow Gradle sync to complete.
4. Select **Build → Build Bundle(s) / APK(s) → Build APK(s)**.
5. The debug APK will be at `app/build/outputs/apk/debug/app-debug.apk`.

Requires JDK 17 and Gradle 8.9+ via Android Studio's Gradle integration.
