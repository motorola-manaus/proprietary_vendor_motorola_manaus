# Motorola Edge 40 Neo (manaus) Vendor Tree

This repository provides proprietary vendor blobs, prebuilt radio firmware, and bootloader binaries for the **Motorola Edge 40 Neo** (`manaus`).

## Contents

* **Radio Firmwares:** Partition images including modem (`md1img.img`), DSP (`audio_dsp.img`), SCP (`scp.img`), SSPM (`sspm.img`), VCP (`vcp.img`), and bootloaders.
* **Patched LK:** Contains the fenrir patched `lk.img` required for fastbootd and custom bootloader compatibility on this device.
* **Camera Prebuilts:** Motorola Camera (`MotCamera4.apk`) and camera tuning blobs (tracked with [Git LFS](https://git-lfs.github.com/)).

## Directory Path in Source Tree

```bash
vendor/motorola/manaus
```

## Git LFS Requirement

Large binaries (such as `MotCamera4.apk`) are tracked using **Git LFS**. When cloning directly, ensure `git-lfs` is installed:

```bash
git lfs install
git clone https://github.com/motorola-manaus/proprietary_vendor_motorola_manaus.git -b seventeen vendor/motorola/manaus
```

## License

* Proprietary binaries extracted from official Motorola firmware release `V1TMS35H.3-45-3-2-7`.
