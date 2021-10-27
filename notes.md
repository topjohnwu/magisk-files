## Magisk (ea75a09f) (23011)

- Make Zygisk survive zygote restarts
- Fix crashes when Magisk environment was not properly setup.
This will fix the crashes experienced after installing Magisk with patching boot images.

## Diffs to v23.0

- [General] MagiskHide is removed from Magisk
- [General] Support 64-bit only systems
- [General] Support Android 12
- [Zygisk] Introduce new feature: Zygisk
- [Zygisk] Introduce DenyList feature to revert Magisk features in user selected processes
- [MagiskBoot] Support patching 32-bit kernel zImages
- [MagiskBoot] Support boot image header v4
- [MagiskInit] Support `/proc/bootconfig` for loading boot configurations
- [MagiskInit] Better support for some Meizu devices
- [MagiskInit] Better support for some Oppo/Realme devices
- [MagiskSU] Use isolated devpts if the kernel supports it
- [resetprop] Deleted properties are now wiped from memory instead of just unlinking
- [App] Build a single APK for all ABIs
- [App] Switch to use standard bottom navigation bar
- [App] Downloading modules within the Magisk app is removed
