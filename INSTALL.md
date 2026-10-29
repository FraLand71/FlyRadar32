# FlyRadar32 1.0 (Build 594) — Web Installer

Install using desktop Google Chrome or Microsoft Edge: https://fraland71.github.io/FlyRadar32/

## UART1 installation

1. Attach a data-capable USB cable to the Waveshare ESP32-S3 Touch LCD 7's **UART1 / USB-to-UART** port.
2. Close Arduino Serial Monitor and other apps occupying the serial port.
3. Open the installer in Chrome/Edge. Click **Install** and select the Waveshare UART serial port.
4. Complete flashing and restart the board. Flashing can erase saved Wi-Fi/location preferences.

Firmware file: `FlyRadar32_v1_0_Build594.ino.merged.bin` (8,388,608 bytes), ESP32-S3 merged image at offset 0.

Previous firmware `FlyRadar_Waveshare7_v5.9.2.ino.merged.bin` is preserved in this repository as a backup.

## Photo library microSD (optional)

Read [microSD instructions](sdcard/README.md). The photos are distributed as a separate Release asset **only after publication and license verification**. Prepare a FAT32/MBR card with the extracted `/foto_compagnie_aeree/` folder.

## Publishing

The installer is hosted by GitHub Pages from `main` / `(root)`. The file `manifest.json` selects the published merged firmware; don't rename the file without updating the manifest.
