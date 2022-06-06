## Magisk (34b2f525) (24316)

- [App] Fix stub app on older Android versions

## Diffs to v24.3

- [MagiskInit] Update 2SI implementation, significantly increase device compatibility (e.g. Sony Xperia devices)
- [MagiskInit] Introduce new `sepolicy` injection mechanism
- [MagiskInit] Support Oculus Go
- [MagiskInit] Support Android 13 GKIs (Pixel 6)
- [MagiskBoot] Fix vbmeta extraction implementation
- [App] [MagiskSU] Properly support apps using shared UID
- [App] Fix stub app on older Android versions
- [MagiskSU] Fix a possible crash in `magiskd`
- [MagiskSU] Prune unused UIDs as soon as possible to prevent UID reuse attacks
- [MagiskSU] Verify and enforce the installed Magisk app's certificate to match the distributor's signature
- [MagiskSU] Handle `system_server` restarts to prevent UID reuse abuse
- [MagiskSU] [Zygisk] Proper package management and detection
- [Zygisk] Fix function hooking on devices running Android 12 with old kernels
- [Zygisk] Fix Zygisk's self code unloading implementation
- [DenyList] Fix DenyList on shared UID apps
- [BusyBox] Add workaround for devices running old kernels
