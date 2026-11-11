# DRINOV AI MUSIC — Android Phase 1

Native Android starter project built with Kotlin and Jetpack Compose.

## Included in Phase 1
- Dark studio-style interface with purple accents
- Home, AI Music Generator, Lyrics Editor, My Music, and Settings screens
- Arabic, French, and English string resources
- Android's locale-aware layout direction (Arabic uses RTL)
- Clean starter boundaries for presentation, domain, and data
- Replaceable AI generation provider interface (no provider or API key configured)
- Basic unit test for the provider contract

## Open and build
1. Install Android Studio (current stable) and an Android SDK.
2. Open this folder in Android Studio.
3. Allow Gradle sync to download the Android Gradle Plugin and dependencies.
4. Run the `app` configuration on an emulator or Android device.

This environment did not include Gradle or the Android SDK, so an APK has **not** been built or tested here.

## Package
`com.drinov.aimusic`

## AI security
Phase 1 defines an API-facing provider contract only. Do not place provider secrets in the Android app. A future secure backend should hold credentials and call the selected music-generation provider.

## Not included yet
- Real AI generation
- Backend/API credentials
- Audio file playback or download implementation
- Authentication, subscriptions, or payments
