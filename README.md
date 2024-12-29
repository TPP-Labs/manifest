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
To start building create a directory and move in that directoery with the command below
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
