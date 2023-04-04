## Magisk (69529ac5) (25211)

- [General] Bump minimum supported Android version to Android 6.0
- [MagiskPolicy] Update rules to support Android U
- [MagiskBoot] Support amonet microloader devices
- [MagiskBoot] Always use lz4_legacy compression on v4 boot images. This fixes boot image patching issues on Android U preview.
- [Zygisk] Rewrite code unloading implementation

## Diffs to v25.2

- [General] Bump minimum supported Android version to Android 6.0
- [General] New magic mount backend. It supports loading modules into system with `overlayfs` files injected
- [Zygisk] Release new API version 4
- [Zygisk] Prevent crashing daemon in error
- [Zygisk] Rewrite zygote code injection with new loader library approach
- [Zygisk] Rewrite code unloading implementation
- [MagiskBoot] Support amonet microloader devices
- [MagiskBoot] Always use lz4_legacy compression on v4 boot images. This fixes boot image patching issues on Android U preview.
- [MagiskInit] Support replacing existing \*.rc files in `overlay.d`
- [MagiskInit] Rewrite sepolicy.rules mounting and loading implementation
- [App] Make stub patching 100% offline
- [App] Support patching `init_boot.img` for Samsung ODIN firmware
- [MagiskPolicy] Fix minor bug in command line argument parsing
- [MagiskPolicy] Update rules to support Android U
