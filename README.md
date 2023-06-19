# NightShadeOS

 Getting Started
---------------
To get started with the NightShadeOS sources, you'll need to get
familiar with [Git and Repo](https://source.android.com/setup/build/downloading).

 To initialize your local repository, use command:

```bash
repo init -u https://github.com/NightShadeOS-Project/manifest.git -b 13
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
lunch nightshade_devicecodename-buildtype
```

Start compilation

```bash
make bacon
```
