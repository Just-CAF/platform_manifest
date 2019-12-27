# Just CAF

## Getting started

To sync and build Just CAF, Android Q:
```
repo init -u git://github.com/Just-CAF/platform_manifest.git -b custom
```
Then to sync up:
```
repo sync -c --no-tags --no-clone-bundle -j$(nproc --all)
```

## Devices

Just CAF is designed for OnePlus 5, msm8998.
