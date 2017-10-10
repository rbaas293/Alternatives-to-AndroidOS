# Alternatives-to-AndroidOS
This tutorial will guide you through installing a new different OS on your android device. This is specifically for users using windows.
# Find a OS for your model of phone
You can google "Android OS alternatives" or follow the links i have below to a few different OS'

  https://itsfoss.com/open-source-alternatives-android/
  https://download.lineageos.org    #LineageOS has the best selection for various models



# What I Chose:
  https://wiki.lineageos.org/devices/jfltexx # LineageOS for Galaxy S4 (International LTE)

NOTE: You can Build from source or Just install, I will be doing the "Just Install" option, as I am time limited.

# Install adb (Android Debug Bridge) and fastboot on your computer:
Follow the following tutorial:

  https://wiki.lineageos.org/adb_fastboot_guide.html#on-macos

Popular adb commands
  adb shell - launches a shell on the device
  adb push <local> <remote> - pushes the file <local> to <remote>
  adb pull <remote> [<local>] - pulls the file <remote> to <local>. If <local> isn’t specified, it will pull to the current folder.
  adb logcat - allows you to view the device log in real-time. You can use adb logcat -b radio to view radio logs, and adb logcat -C to view logs in colour
  adb install <file> - installs the given .apk file to your device

If you want google apps on the new install get them at:

  https://wiki.lineageos.org/gapps.html

    adb push lineage-14.1-20171004-nightly-jfltexx-signed.zip /sdcard/
    adb push open_gapps-arm-7.1-nano-20171009.zip /sdcard/
    adb push addonsu-14.1-arm-signed.zip /sdcard/
