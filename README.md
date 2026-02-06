# EDC15P+ IMMO & DTC Tool

> ⚠️ **BETA VERSION** - This is a test release. Use at your own risk.

Android tool for EDC15P+ ECU modifications - IMMO OFF/ON and DTC removal.

## Features

- 🔓 IMMO OFF/ON toggle
- 🔧 DTC (Diagnostic Trouble Codes) removal
- 📊 ECU info extraction (part number, software version)
- 📱 100% Offline - no internet required
- 💾 Save modified files to Downloads

## ⚠️ Disclaimer

This is a **test version**. The developer is not responsible for any damage to your vehicle or ECU. Always:
- Backup your original file before making changes
- Verify the checksum before flashing
- Use at your own risk

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

APK output: `EDC15P-APK/output/EDC15P-Tool.apk`

## Usage

1. Open the app
2. Select a .bin file (max 600KB)
3. Review ECU analysis
4. Select operations (IMMO OFF, DTC removal)
5. Process and download modified file
6. **Always fix checksum before flashing!**

## Supported ECUs

- Bosch EDC15P+ (VAG)
- Part numbers: 038 906 xxx

## License

MIT
