# AOSP-O FOR KENZO #

### Sync ###



# Initialize local repository
```bash
repo init -u https://github.com/AOSP-O/android_manifest -b oreo
```

# Sync
```bash
repo sync --force-sync --force-broken --no-clone-bundle --no-tags -j2
```

### Preparing to Build ###



# Set up environment
```bash
$ . build/envsetup.sh
```

# Choose a target
```bash
$ lunch aosp_kenzo-userdebug
```

# Build the code
```bash
$ mka bacon -jX
```
