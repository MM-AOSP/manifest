The Android Open Source Project Marsmallow 6.0.1
===========

To initialize your local repository using the AOSP trees, use a command like this:
````bash
repo init -u git://github.com/MM-AOSP/manifest.git -b mm6.0
```
Then to sync up:
````bash
repo sync
```
Finally to build:
````bash
./build.sh device_codename
```
Example:
````bash
./build.sh falcon
```
