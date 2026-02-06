# EDC15P+ IMMO & DTC Tool

Android tool for EDC15P+ ECU modifications - IMMO OFF/ON and DTC removal.

## Features

- 🔓 IMMO OFF/ON toggle
- 🔧 DTC (Diagnostic Trouble Codes) removal
- 📊 ECU info extraction (part number, software version)
- 📱 100% Offline - no internet required
- 💾 Save modified files to Downloads

## Download

Get the latest APK from [Releases](../../releases).

## Build from Source

### Requirements

- Java 17
- Android SDK 35
- Gradle

### Compile

```bash
cd EDC15P-APK/platforms/android
./gradlew assembleDebug
```

APK will be at `app/build/outputs/apk/debug/app-debug.apk`

## Usage

1. Open the app
2. Select a .bin file (max 600KB)
3. Review ECU analysis
4. Select operations (IMMO OFF, DTC removal)
5. Process and download modified file

## Supported ECUs

- Bosch EDC15P+ (VAG)
- Part numbers: 038 906 xxx

## License

MIT
