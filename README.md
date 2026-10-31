# Peachy Daily Planner

A fresh native Android project for an offline-friendly cute planner.

## Features in this starter version
- Lavender, Pink, Peach, Sage, Baby Blue and Vanilla themes
- Font family choices (Simple, Serif, Typewriter)
- Pick a photo from Gallery (saved as the selected wallpaper preference)
- To-do list with checkboxes and delete
- Notes saved automatically
- Cute emoji sticker corner
- Designed to adapt to tablet and phone layouts

## Build an APK using GitHub Actions
1. Upload the contents of this ZIP to a new GitHub repository (not the ZIP file itself).
2. Open the repository's **Actions** tab.
3. Choose **Build Peachy Daily Planner APK**.
4. Tap **Run workflow** and wait for it to finish.
5. Open the completed workflow run, scroll to **Artifacts**, and download **Peachy-Daily-Planner-APK**.
6. Extract the downloaded artifact ZIP and install `app-debug.apk` on your Android tablet. Allow installation from that source if Android asks.

## Build locally
Open this folder in Android Studio, install Android SDK 35 and JDK 17, then run:
`gradle assembleDebug`

This is a starter project. The chosen Gallery image is remembered, but applying that image as a full-screen background and movable sticker placement are not yet implemented.
