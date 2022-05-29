## Magisk (bf04fa13) (24314)

- [App] Fix language switch
- [MagiskSU] Handle `system_server` restarts to prevent UID reuse abuse

## Diffs to v24.3

- [MagiskInit] Update 2SI implementation, significantly increase device compatibility (e.g. Sony Xperia devices)
- [MagiskInit] Introduce new `sepolicy` injection mechanism
- [MagiskInit] Support Oculus Go
- [MagiskInit] Support Android 13 GKIs (Pixel 6)
- [MagiskBoot] Fix vbmeta extraction implementation
- [App] [MagiskSU] Properly support apps using shared UID
- [MagiskSU] Fix a possible crash in `magiskd`
- [MagiskSU] Prune unused UIDs as soon as possible to prevent UID reuse attacks
- [MagiskSU] Verify and enforce the installed Magisk app's certificate to match the distributor's signature
- [MagiskSU] Handle `system_server` restarts to prevent UID reuse abuse
- [Zygisk] Fix function hooking on devices running Android 12 with old kernels
- [DenyList] Fix DenyList on shared UID apps
- [BusyBox] Add workaround for devices running old kernels
