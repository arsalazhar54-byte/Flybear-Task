# Flybear Task Android project

This project wraps the Flybear Task warehouse tracker in a native Android WebView shell.

## Features
- Daily task list with priorities, completion, delete, and carry-over
- Inbound carton/piece totals, sorting, rack placement, tagging
- Order assignment, picking and refill logs
- Break log, prayer-time checklist, closing-time settings
- Closing checklist with photos and daily results sheet
- Data stored locally in WebView storage on the device

## Build the APK
### Easiest route: GitHub Actions
1. Create a new GitHub repository.
2. Upload the contents of this folder to the repository (not the ZIP itself).
3. Open **Actions** → **Build Flybear Task APK** → **Run workflow**.
4. When the run finishes, open it and download the `FlybearTask-debug-apk` artifact.
5. Extract the artifact ZIP and install `app-debug.apk` on your Android phone. Android may ask you to allow installs from that source.

### Build locally
Open this folder in Android Studio with Android SDK 35 installed, then build the `app` debug APK.

## Important notes
- The APK is a debug build for personal use, not a Play Store release.
- Data is stored on the phone and is not automatically synced or backed up.
- The reminder banner only appears while the app is open; it is not a background alarm.
- Closing photos are resized before saving to reduce storage use.
