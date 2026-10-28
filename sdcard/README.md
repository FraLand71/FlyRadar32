# FlyRadar32 — Aircraft photo library (microSD)

The optional aircraft photo library is distributed separately from the firmware.

## Prepare the microSD

1. Back up existing files. Format a compatible card as **FAT32**, **MBR** partition scheme (not exFAT). The volume label can be `FLYRADAR32`.
2. Download `foto_compagnie_aeree.zip` from the FlyRadar32 GitHub Release once that Release is published.
3. **Extract** the ZIP. Copy the folder `foto_compagnie_aeree` to the **root of the microSD**. Do not copy the ZIP file itself.
4. Verify these paths exist on the card:

```text
/foto_compagnie_aeree/mappa_codici.json
/foto_compagnie_aeree/catalogo.json
/foto_compagnie_aeree/images/
```

5. Insert the card into the Waveshare ESP32-S3 Touch LCD 7 while powered off. Restart FlyRadar32.

The letter **S** near the aircraft photo denotes a picture loaded from the microSD; **I** denotes an Internet picture. The onboard fallback may show a different indicator.

## Photo credits and redistribution

Consult the archive's `CREDITI.txt` and individual photo metadata for source and license. Do not redistribute assets unless the license or rightsholder allows it; give attribution and fulfill any share-alike and license-link requirements. If permissions are unclear, keep the GitHub Release in Draft and publish only after review.

## Notes

Firmware and photo archive are separate. Updating the firmware does not install these images, and flashing firmware does not normally change files on the microSD.
