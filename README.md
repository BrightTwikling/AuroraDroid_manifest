Getting Started:
 ==============

To get started with AuroraDroid, you'll need to get familiar with [Repo](https://source.android.com/source/using-repo.html) and Version Control with [Git](https://source.android.com/source/version-control.html).

To initialize your local repository, use a command like this:

```bash
repo init -u https://github.com/AuroraDroid/manifest -b 15 --git-lfs
```

Then to sync up:

```
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```
---------------------------------------------------------------------------------------
 Building AuroraDroid:
 ====================

From root directory of Project, perform following commands in terminal

```bash
$ . build/envsetup.sh
$ lunch aurora_$device-ap3a-userdebug
$ make bacon
```
# Credits:

 * [**LineageOS**](https://github.com/LineageOS)
