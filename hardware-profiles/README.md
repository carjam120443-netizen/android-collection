# Android OS Hardware Profiles

This directory is organized by **company/vendor and Android OS family**. It contains real hardware-profile XML files where available, plus clearly marked placeholders for profiles we plan to add.

## Company Android OS families

### Samsung
- One UI — Samsung's Android-based mobile OS experience
- Galaxy S / S FE / S Ultra — hardware profiles
- Galaxy A — hardware profiles
- Galaxy Note — legacy hardware profiles
- Galaxy Z — foldable hardware profiles
- Galaxy Tab — tablet hardware profiles

### Google
- Pixel Android — Google Pixel devices
- Pixel UI — Google's Pixel software experience
- Android Open Source Project (AOSP) — baseline Android system images

### Xiaomi
- MIUI — Xiaomi's former Android-based software platform
- HyperOS — Xiaomi's current Android-based platform
- Redmi — device family profiles
- POCO — device family profiles

### OnePlus
- OxygenOS — OnePlus Android-based OS
- OnePlus device profiles

### OPPO
- ColorOS — OPPO Android-based OS
- Find series profiles
- Reno series profiles

### vivo
- Funtouch OS — vivo Android-based OS
- OriginOS — vivo's Android-based OS used in some markets

### HONOR
- MagicOS — HONOR Android-based OS
- Magic series profiles

### Huawei
- EMUI — Huawei's Android-based legacy OS
- HarmonyOS — Huawei's platform; compatibility with Android AVDs varies by release/device

### Motorola / Lenovo
- My UX — Motorola Android software experience
- Hello UI — newer Motorola Android software experience
- Moto device profiles

### Sony
- Xperia Android — Sony Xperia device profiles
- Xperia UI — Sony's Android software experience

### ASUS
- ZenUI — ASUS Android software experience
- ROG UI — ASUS gaming-phone software experience
- Zenfone / ROG Phone profiles

### Nothing
- Nothing OS — Nothing Android-based OS
- Phone series profiles

### Nokia / HMD
- Nokia Android — HMD/Nokia Android devices
- HMD Android device profiles

### LG
- LG UX — legacy LG Android software experience
- LG device profiles

### HTC
- HTC Sense — legacy HTC Android software experience
- HTC device profiles

### Fairphone
- Fairphone Android — Fairphone Android devices
- Fairphone profiles

### ZTE / nubia
- MyOS — ZTE Android software experience
- nubia UI / MyOS device profiles

### TCL
- TCL UI — TCL Android software experience
- TCL device profiles

### Nothing / other Android vendors
- Additional vendors can be added here as profiles are sourced and verified.

## Placeholder policy

A placeholder means **the OS/device family is documented here, but an XML hardware profile has not been imported yet**. Placeholders are not claimed to be functional AVD profiles.

Suggested placeholder filename pattern:

```text
hardware-profiles/<company>/<device>.xml.placeholder
```

Do not put fake XML in a real `.xml` file and present it as working hardware data. When a real profile is found, replace the placeholder with the verified XML and record its source in `sources/SOURCES.md`.

## Current real profiles

- `samsung/galaxy_s8.xml`
- `samsung/galaxy_s21.xml`
- `samsung/galaxy_s21_fe.xml`
- `google/pixel_5.xml`
