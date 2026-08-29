# FIHIRANA AGAPAO TABERNACLE

Fihirana 2024 — Android offline hymn book built from the supplied `Fihirana 2024.pdf` only.

## Features
- 295 structured hymns in `app/src/main/assets/hymns.json`
- Offline search by number, title and lyrics
- Favorites saved with DataStore
- Font size A− / A+ saved locally
- Previous / Next hymn navigation by sorted hymn entries
- About page
- Footer: `Éditeur : Pasteur Zo`

## Source accuracy
See `VALIDATION_REPORT.md` and `VALIDATION_REPORT.json`.

## Build
Open the project in Android Studio, allow Gradle sync, then run:

`./gradlew assembleDebug`

APK output:
`app/build/outputs/apk/debug/app-debug.apk`

For a release APK, configure a signing key in Android Studio and use Build > Generate Signed Bundle / APK.
