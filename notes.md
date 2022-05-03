## Magisk (cc79a96f) (24307)

- [App] Update libsu with 100% new I/O layer
- [MagiskInit] Mock enforce file with regular file to prevent possible race condition
- Switch normal NDK with ONDK, preparing the toolchain to introduce Rust

## Diffs to v24.3

- [MagiskInit] Update 2SI implementation, significantly increase device compatibility (e.g. Sony Xperia devices)
- [MagiskInit] Introduce new `sepolicy` injection mechanism
- [MagiskInit] Support Oculus Go
- [App] [MagiskSU] Properly support apps using shared UID
- [MagiskSU] Fix a possible crash in `magiskd`
- [Zygisk] Fix function hooking on devices running Android 12 with old kernels
- [BusyBox] Add workaround for devices running old kernels
