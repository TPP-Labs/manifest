AOSPB
===========

Getting started
---------------

To get started with Android/aospb, you'll need to get familiar with [Source Control Tools](https://source.android.com/setup/develop).

### Spinning up the environment
--------------
```bash
bash <(curl -sL https://raw.githubusercontent.com/akhilnarang/scripts/refs/heads/master/setup/android_build_env.sh)
```

Start Syncing
---------------
To start syncing, create a directory and move in that directoery with the command below.
```
mkdir aospb && cd aospb
```

To initialize your local repository using the aospb trees, use a command like this:
```
repo init -u https://github.com/aospb-staging/manifest.git -b 15.1 --git-lfs
```
Then to sync up:
```
repo sync
```
Start Building
---------------
To start the building process, setup the environment by executing the below command.
```
source build/envsetup.sh
```
Use the below command to perform lunch action, replace *$device_codename* as required for your device. 

```
breakfast $device_codename
```

To start the build:
```
brunch $device_codename
```
**Note**: By default `user` build is set.

### Credits
--------------
 * [**AOSP**](https://android.googlesource.com)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**AOSPA**](https://github.com/AOSPA)
 * [**HentaiOS**](https://github.com/hentaios)
 * [**Project Radiant**](https://github.com/ProjectRadiant)
 * [**PixelOS-AOSP**](https://github.com/PixelOS-AOSP)
 * [**StatixOS**](https://github.com/StatiXOS)
 * [**Project Pixelage**](https://github.com/ProjectPixelage)
 * [**cAOSP**](https://github.com/c0smic-Lab)
 * ... And the list never ends.
