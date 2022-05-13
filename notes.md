## Magisk (c11ccbae) (24310)

- [MagiskBoot] Fix vbmeta extraction implementation

## Diffs to v24.3

- [MagiskInit] Update 2SI implementation, significantly increase device compatibility (e.g. Sony Xperia devices)
- [MagiskInit] Introduce new `sepolicy` injection mechanism
- [MagiskInit] Support Oculus Go
- [MagiskInit] Support GKIs with no ramdisk (Pixel 6 Android 13)
- [MagiskBoot] Fix vbmeta extraction implementation
- [App] [MagiskSU] Properly support apps using shared UID
- [MagiskSU] Fix a possible crash in `magiskd`
- [Zygisk] Fix function hooking on devices running Android 12 with old kernels
- [BusyBox] Add workaround for devices running old kernels
