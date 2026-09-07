# Android system-image references

System images are intentionally not stored in this repository because the ZIP archives are large and can have their own distribution terms.

## Official Android sources

Use Android Studio SDK Manager for the current AOSP, Google APIs, and Google Play images.

- Android Developers — SDK platforms and system images: https://developer.android.com/tools/releases/platforms
- Android Developers — AVD management: https://developer.android.com/studio/run/managing-avds

## Recommended categories

- `aosp/` — useful for emulator development/testing and elevated ADB workflows where supported
- `google-apis/` — Google APIs without the Play Store image restrictions
- `google-play/` — Play Store-enabled images for app compatibility testing

Always check the specific image's documentation and signing/privilege behavior; a hardware profile or skin does not determine root access.
