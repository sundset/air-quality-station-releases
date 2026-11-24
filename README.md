# LUFTIG firmware releases

Signed firmware releases for the Freenove FNK0104N ESP32-S3 air-quality station. The station's local display, simulated measurements and microSD history remain available offline.

## On the station

On firmware with OTA support, open **Om → Sök efter uppdatering**. Select an update to download it, then confirm installation and restart on the touchscreen.

## Release assets

Each versioned release contains:

- `firmware.bin` — the FNK0104N application image.
- `firmware.sig` — the ECDSA P-256 signature for the firmware metadata.
- `version.json` — the device, version, size, SHA-256, download URLs and release notes for that build.

The stable channel uses `main/version.json`. That file is created on the first approved release and updated only after the versioned assets have been published and verified.

[Browse firmware releases](https://github.com/sundset/air-quality-station-releases/releases)
