# AOSP-O FOR KENZO #

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/AOSP-O/android_manifest -b oreo

# Sync
repo sync -c -jx --force-sync --no-clone-bundle --no-tags
```

### Preparing to Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch aosp_kenzo-userdebug

# Build the code
$ mka bacon -jX
```
