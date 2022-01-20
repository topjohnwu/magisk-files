## Magisk (5f4cd50c) (23017)

- [MagiskInit] Fallback to default fstab if dt fstab contains errors
- [MagiskInit] Skip loading Magisk when detecting DSU
- [DenyList] Support listing, adding, and removing processes from the denylist regardless of enforcement status
- [Zygisk] Add new APIs (not finalized yet, please wait for actual publication)
- [App] Support user configuration of boot image vbmeta patching
- [App] Add DNS-Over-HTTPS option back
- [App] Restore the ability to install Magisk on the other slot on some A/B devices
- [App] Partial module update checking support (not complete, still WIP)
- [App] Many bug fixes

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
- [MagiskBoot] Add new env variable `PATCHVBMETAFLAG` to configure whether vbmeta flags should be patched
- [MagiskInit] Support loading fstab from `/system/etc` (required for Pixel 6)
- [MagiskInit] Support `/proc/bootconfig` for loading boot configurations
- [MagiskInit] Better support for some Meizu devices
- [MagiskInit] Better support for some OnePlus/Oppo/Realme devices
- [MagiskInit] Support `init.real` on some Sony devices
- [MagiskInit] Skip loading Magisk when detecting DSU
- [MagiskPolicy] Load `*_compat_cil_file` from system_ext
- [MagiskSU] Use isolated devpts if the kernel supports it
- [MagiskSU] Fix root shell if isolated mount namespace is set
- [resetprop] Deleted properties are now wiped from memory instead of just unlinking
- [App] Build a single APK for all ABIs
- [App] Switch to use standard bottom navigation bar
- [App] Downloading modules from the centralized Magisk-Modules-Repo is removed
- [App] Support user configuration of boot image vbmeta patching
- [App] Restore the ability to install Magisk on the other slot on some A/B devices
