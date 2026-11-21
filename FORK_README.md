# UNITRONIX Bliss OS typhoon-x86 manifest fork

Public fork of BlissOS/platform_manifest (`typhoon-x86`).

Key components (device, Mesa/HWC/gralloc, kernel, audio, hardware interfaces)
resolve from **UNITRONIX** GitHub forks via `unitronix-overrides.xml`.

## Sync the same workspace

```bash
mkdir bliss-typhoon && cd bliss-typhoon
repo init -u https://github.com/UNITRONIX/platform_manifest.git -b typhoon-x86 --git-lfs
repo sync -c --no-tags --no-clone-bundle -j$(nproc) --optimized-fetch --prune
```

Based on BlissOS / AOSP / Android-x86. Not an official BlissOS release.
