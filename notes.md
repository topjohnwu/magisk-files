## Magisk (63a89d9f) (24306)

- [App] Fix incorrect superuser snackbar text
- [MagiskInit] Improvements to sepolicy hijack
- [MagiskInit] Use `LD_PRELOAD` on 2SI init to assist hijack
- [MagiskInit] Support Oculus Go
- [MagiskSU] Fix a possible crash in `magiskd`

## Diffs to v24.3

- [MagiskInit] Update 2SI implementation, significantly increase device compatibility (e.g. Sony Xperia devices)
- [MagiskInit] Introduce new `sepolicy` injection mechanism
- [MagiskInit] Support Oculus Go
- [App] [MagiskSU] Properly support apps using shared UID
- [MagiskSU] Fix a possible crash in `magiskd`
- [Zygisk] Fix function hooking on devices running Android 12 with old kernels
- [BusyBox] Add workaround for devices running old kernels
