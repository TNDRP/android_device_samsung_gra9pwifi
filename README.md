## TWRP tree for Samsung Galaxy Tab A9+ Wifi (gta9pwifi)
Build your first custom recovery from TeamWin Recovery Project.

# Clone
    git clone https://github.com/TNDRP/android_device_samsung_gta9p.git -b twrp-12.1 device/samsung/gta9pwifi

# Build
    export ALLOW_MISSING_DEPENDENCIES=true; . build/envsetup.sh; lunch twrp_gta9pwifi-eng; mka recoveryimage
