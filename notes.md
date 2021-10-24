## Magisk (d7e7df3b) (23010)

A new chapter for Magisk!

For those who missed my blog post, please check [here](https://topjohnwu.medium.com/state-of-magisk-2021-fe29fdaee458?source=friends_link&sk=2baadecfa78cbba8a41671e13b244bf1)

## Diffs to v23.0

- [General] MagiskHide is removed from Magisk
- [General] Support 64-bit only systems
- [General] Support Android 12
- [Zygisk] Introduce new feature: Zygisk
- [Zygisk] Introduce DenyList feature to revert Magisk features in use selected processes
- [MagiskBoot] Support patching 32-bit kernel zImages
- [MagiskBoot] Support boot image header v4
- [MagiskInit] Support `/proc/bootconfig` for loading boot configurations
- [MagiskInit] Better support for some Meizu devices
- [MagiskInit] Better support for some Oppo/Realme devices
- [MagiskSU] Use isolated devpts if the kernel supports it
- [resetprop] Deleted properties are now wiped from memory instead of just unlinking
- [App] Build a single APK for all ABIs
- [App] Switch to use standard bottom navigation bar
- [App] Downloading modules the Magisk app is removed
