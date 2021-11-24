## Magisk (5d6d2417) (23015)

- Cleanup unclosed fds leftover from Zygisk modules
- Fix parallel app info fetching in DenyList UI to speed things up
- Export `ZYGISK_ENABLED` to boot scripts if Zygisk is enabled
- Fix v4 vendor boot unpacking/repacking
- Add new env variable `KEEPVBMETAFLAG` to toggle configure vbmeta flags should be preserved
- Update BusyBox to 1.34.1

## Diffs to v23.0

- [General] MagiskHide is removed from Magisk
- [General] Support 64-bit only systems
- [General] Support Android 12
- [General] Update BusyBox to 1.34.1
- [Zygisk] Introduce new feature: Zygisk
- [Zygisk] Introduce DenyList feature to revert Magisk features in user selected processes
- [MagiskBoot] Support patching 32-bit kernel zImages
- [MagiskBoot] Support boot image header v4
- [MagiskBoot] Support patching out `skip_initramfs` from dtb bootargs
- [MagiskBoot] Add new env variable `KEEPVBMETAFLAG` to configure whether vbmeta flags should be preserved
- [MagiskInit] Support `/proc/bootconfig` for loading boot configurations
- [MagiskInit] Better support for some Meizu devices
- [MagiskInit] Better support for some Oppo/Realme devices
- [MagiskInit] Support `init.real` on some Sony devices
- [MagiskPolicy] Load `*_compat_cil_file` from system_ext
- [MagiskSU] Use isolated devpts if the kernel supports it
- [MagiskSU] Fix root shell if isolated mount namespace is set
- [resetprop] Deleted properties are now wiped from memory instead of just unlinking
- [App] Build a single APK for all ABIs
- [App] Switch to use standard bottom navigation bar
- [App] Downloading modules within the Magisk app is removed
