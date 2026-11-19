# KAMII STORE Android App

This is a simple Android WebView app that opens the KAMII STORE website:
https://kamiistorepk0.netlify.app

## Build APK with GitHub Actions
1. Upload the contents of this project to your GitHub repository (keep the folder structure).
2. Open the repository's **Actions** tab.
3. Select **Build Android APK** workflow and tap **Run workflow** (or push to main).
4. When the workflow finishes, open its run and download the `KAMII-STORE-debug-apk` artifact.

## Project structure
- `app/src/main/java/com/kamii/store/MainActivity.java` — WebView app
- `app/src/main/AndroidManifest.xml` — permissions and launcher activity
- `app/build.gradle` — app configuration
- `build.gradle` — Android Gradle plugin
- `.github/workflows/build-apk.yml` — automated APK build
