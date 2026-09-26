# Cat Defense Game Source V6

V6 continues the V5 Android/Kotlin offline prototype while preserving the original Craftpix runtime assets.

## V6 changes
- Enemy and boss rendering now uses supplied Walk/Attack/Dead animation folders instead of invalid Hit/Dead lookups.
- Cat rendering uses supplied Idle/Shoot frames only; no Cat Dead asset is invented.
- Projectile variants are differentiated by cat type and damage multiplier.
- Five skill archetypes are distributed across the 15 cats: Rapid Fire, Power Shot, Double Shot, Splash, Critical Burst.
- Boss area skill and explosion effect retained.
- Focus target, drag deployment (maximum 3 cats), waves, boss wave, save, shop, level map, settings and pause retained.
- No audio files were present in the supplied asset set, so sound/vibration switches remain saved settings only.

## Build note
A complete Android SDK/Gradle toolchain was not available in the generation environment, so APK compilation is not claimed as verified. Import the project into Android Studio or another compatible Android build environment.
