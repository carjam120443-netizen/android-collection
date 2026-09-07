# Android Collection

A curated collection of Android Studio AVD hardware profiles, emulator skins, system-image references, and tools.

## Structure

- `avds/` — AVD manifests and curated combinations
- `hardware-profiles/` — Importable Android Studio hardware-profile XMLs
  - `google/`
  - `samsung/`
  - `other/`
- `skins/` — Emulator skin references and installation notes
  - `samsung/`
  - `community/`
- `system-images/` — System-image references and metadata (large ZIPs are not vendored)
  - `aosp/`
  - `google-apis/`
  - `google-play/`
- `tools/` — Emulator/AVD helper scripts and notes
- `sources/` — Upstream/source URLs and attribution

## Sources

This collection draws from official Android/Samsung resources and community hardware-profile projects, including:

- Android Developers — AVD management and custom skins
- Samsung Developers — Galaxy Emulator Skins
- ugglr/android-virtual-devices — community hardware profiles
- Jiff21/AVD-devices — community hardware profiles and skins
- React-Native-Nation/Hardware-Profiles-For-Android-Studio — community hardware profiles and skins

## Important

Hardware profiles and skins do not contain an Android operating system. An AVD combines a hardware profile with a system image. Large system-image archives are intentionally referenced rather than copied into this repository.

## Licensing

Each imported or referenced item remains subject to its upstream project's license and terms. See `sources/` for provenance.
