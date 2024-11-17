# ProjectBlaze Reborn

 Getting Started
---------------
To get started with the ProjectBlaze Reborn sources, you'll need to get
familiar with [Git and Repo](https://source.android.com/setup/build/downloading).

 To initialize your local repository, use command:

```bash
repo init -u https://github.com/ProjectBlaze-Reborn/manifest.git -b 15 --git-lfs --depth=1
```

Then sync up:

```bash
repo sync
```

Building the System
-------------------
 Initialize the ROM environment with the envsetup.sh script.

```bash
. build/envsetup.sh
```

Lunch your device after cloning all device sources if needed.

```bash
lunch blaze_devicecodename-ap3a-buildtype
```

Start compilation

```bash
mka bacon
```

Or you can just do brunch

```bash
brunch devicecodename buildtype
```
