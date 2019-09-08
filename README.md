# COSP #

This is WIP!

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/cosp-project/manifest -b ten

# Sync
repo sync -c -jX --no-clone-bundle --no-tags

where X in -jX is number of projects to fetch simultaneously 
```

### Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch cosp_$device-userdebug

# Build the code
$ mka bacon -jX
```