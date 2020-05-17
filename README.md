# BICPR🍒  #

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/BICPR/manifest -b ten

# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch aosp_$device-userdebug

# Build the code
$ mka bacon -jX
```

### Submitting Patches ###

Patches are always welcome!  You can always submit a pull requiest :)
