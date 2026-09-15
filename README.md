# Infinix Retail Intelligence — Android

Simple Android WebView app for the live Infinix Retail Intelligence dashboard.

## App URL
https://infinix-retail-intelligence-hub-arslanbabar979-9623.vercel.app/

## Included
- Persistent web login/session
- Android back navigation
- PSI / Excel file picker support
- Download support
- Internet error/retry page
- GitHub Actions workflow that builds a debug APK

## Build locally
Open in Android Studio and run the `app` module, or use Gradle with Android SDK installed.

## Build on GitHub
Every push to `main` runs the `Build Android APK` workflow. The workflow builds `app-debug.apk` and uploads it as an artifact named `Infinix-Retail-Intelligence-APK`.
