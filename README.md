Droidian
========

Droidian is a GNU/Linux distribution based on top of Mobian, a Debian-based distribution for mobile devices. The goal of Droidian is to be able to run Mobian on Android phones.

Droidian for Sony Xperia 5 II (PDX206)
========

This repository contains rootfs image build scripts for a community port of Droidian to Sony Xperia 5 II (PDX206).

To install the image, follow the steps below:

1. Make sure that **both slots** (A/B) of your device are flashed with the latest **official** Android 11 firmware.
2. Download the corresponding flashable rootfs image [here](https://github.com/PeterCxy/droidian-recipes/releases/tag/nightly).
3. Boot your phone into bootloader mode by connecting your phone to a Linux PC while holding Volume UP.
4. Extract the zip file downloaded, run `flash_all.sh` from your Linux PC.
5. Reboot and enjoy.
