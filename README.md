# OrangeFox Recovery Project for the Samsung Galaxy A40

### How to build ###

```bash
# Create dirs
$ mkdir ofox ; cd ofox

# Init repo
$ repo init --depth=1 -u https://gitlab.com/OrangeFox/Manifest.git -b fox_9.0

# Clone a40 repo
$ git clone https://gitlab.com/OrangeFox/device/a40.git -b fox_9.0 device/samsung/a40

# Sync
$ repo sync --no-repo-verify -c --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune -j`nproc`

# Build
$ source build/envsetup.sh ; lunch omni_a40-eng ; mka recoveryimage
```
## Credits
2020 @Astrako

## Contact
Telegram support group: https://t.me/joinchat/D1Jk_VbieGBXOWZt2y8O7A
