# Curated AVD combinations

These are recipes for combining a hardware profile, Android system image, and optional skin.

| AVD | Hardware profile | Suggested image | Skin |
|---|---|---|---|
| Galaxy S8 AOSP | `hardware-profiles/samsung/galaxy_s8.xml` | AOSP x86_64 | Samsung Galaxy S8 skin |
| Pixel 5 AOSP | `hardware-profiles/google/pixel_5.xml` | AOSP x86_64 | Optional Pixel/community skin |
| Galaxy S8 Google APIs | `hardware-profiles/samsung/galaxy_s8.xml` | Google APIs x86_64 | Samsung Galaxy S8 skin |

A hardware profile does not make an Android image rooted. Root/elevated ADB behavior depends on the selected system image and emulator configuration.

For current images, use Android Studio SDK Manager rather than committing multi-gigabyte system-image archives to this repository.
