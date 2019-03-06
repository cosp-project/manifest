# COSP #

Find our gerrit [here](https://gerrit.cosp-project.org).

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/cosp-project/manifest -b pie

# Sync
repo sync -c -jx --force-sync --no-clone-bundle --no-tags
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
