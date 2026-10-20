# FlyRadar32 web installer

Open https://fraland71.github.io/FlyRadar32/ in desktop Chrome/Edge.

## Firmware upload (required)
Upload the exact file `FlyRadar_Waveshare7_v5.9.2.ino.merged.bin` (8,388,608 bytes) to the **root of the main branch**, alongside `index.html` and `manifest.json`. No rename.

## GitHub Pages
Repository Settings → Pages → Build and deployment: Deploy from a branch → Branch `main`, Folder `/(root)` → Save. Wait for deployment.

## Notes
This is a merged binary for ESP32-S3 to flash at offset 0. The microSD pictures are separate. Installation may erase Wi-Fi or location settings. Back up working firmware before flashing.
