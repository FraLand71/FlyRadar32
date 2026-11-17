# FlyRadar32 1.2 (Build 694) — Web Installer

**Install:** https://fraland71.github.io/FlyRadar32/

Device: **Waveshare ESP32-S3 Touch LCD 7″ (800 × 480)**. Use **desktop Google Chrome or Microsoft Edge** (Web Serial).

## USB installation

1. Connect the board with a USB data cable. For the native ESP32-S3 USB port, disconnect power, hold **BOOT**, reconnect USB, and release **BOOT**. Alternatively, use the Waveshare **UART1 USB-to-serial** port.
2. Close Arduino Serial Monitor, ESP-IDF monitor, and other applications using the serial port.
3. Open the web installer, click **Install**, and select the detected Waveshare serial port.
4. Complete flashing, then disconnect and reconnect power **without** holding BOOT. Flashing may erase saved Wi-Fi/location preferences.

## Firmware

- **Current:** `FlyRadar32_v1_2_Build694_merged.bin`
- **Size:** 2,318,944 bytes
- **Target:** ESP32-S3
- **Flash offset:** `0x0`
- **Display configuration:** ESP-IDF RGB64 (Waveshare 7″)

Build 690 remains in the repository as a fallback. Do not select another .bin when installing Build 694.

## microSD photographs (optional)

Read [microSD instructions](sdcard/README.md). The optional photo library is **not** embedded in the firmware. Prepare a FAT32/MBR card with the extracted `/foto_compagnie_aeree/` folder.

## Publishing

GitHub Pages serves the site from the `main` branch root. The `manifest.json` file points to the merged firmware at offset 0; changing the firmware filename also requires updating the manifest and cache-busting revision. Photo archive publication is separate and subject to license verification.
