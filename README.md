Local manifests to build CyanogenMod 11 for [HTC Desire C]

How to build:
-------------

Initialize repo:

    repo init -u git://github.com/CyanogenMod/android.git -b cm-11.0
    curl --create-dirs -L -o .repo/local_manifests/local_manifest.xml -O -L https://raw.githubusercontent.com/high1/android_local_manifest/cm-11.0/local_manifest.xml
    repo sync

Compile:

    . build/envsetup.sh
    brunch golfu