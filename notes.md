## Magisk (985249c3) (24309)

Pixel 6 Android 13 Beta 2 support is here!

- [App] Support requesting root from non app process
- [App] Fix deadlocking a background thread on non-root devices
- [MagiskInit] Support GKIs with no ramdisk (Pixel 6 Android 13)

## Diffs to v24.3

- [MagiskInit] Update 2SI implementation, significantly increase device compatibility (e.g. Sony Xperia devices)
- [MagiskInit] Introduce new `sepolicy` injection mechanism
- [MagiskInit] Support Oculus Go
- [MagiskInit] Support GKIs with no ramdisk (Pixel 6 Android 13)
- [App] [MagiskSU] Properly support apps using shared UID
- [MagiskSU] Fix a possible crash in `magiskd`
- [Zygisk] Fix function hooking on devices running Android 12 with old kernels
- [BusyBox] Add workaround for devices running old kernels
