# Flybear Task Android

Orange-themed warehouse task tracker wrapped in an Android WebView. Features include task/stock/order tracking, photo add/delete, previous storage records, progress/results, settings, five themes, welcome/login/sign-up demo screens, mascot background, and launcher icon.

## Build APK with GitHub Actions
Commit the contents of this project folder to the repository root (so `app/`, `build.gradle`, `settings.gradle`, and `.github/workflows/` are at the root). Open **Actions → Build Flybear Task APK → Run workflow**. Download the `FlybearTask-APK` artifact from a successful run.

## Important note about login
Login/sign-up is a local demonstration only; it does not authenticate users on a server or sync records between devices. Do not use a real sensitive password. Data is stored in the browser/WebView on this device.
