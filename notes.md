## Magisk (7dbfba76) (25207)

- [General] New magic mount backend. It supports loading modules into system with `overlayfs` files injected
- [MagiskInit] Support replacing existing \*.rc files in `overlay.d`
- [MagiskInit] Rewrite sepolicy.rules mounting and loading implementation
- [Zygisk] Release new API version 4
- [App] Support patching `init_boot.img` for Samsung ODIN firmware

## Diffs to v25.2

- [General] New magic mount backend. It supports loading modules into system with `overlayfs` files injected
- [MagiskPolicy] Fix minor bug in command line argument parsing
- [Zygisk] Prevent crashing daemon in error
- [Zygisk] Rewrite zygote code injection with new loader library approach
- [Zygisk] Release new API version 4
- [App] Make stub patching 100% offline
- [App] Support patching `init_boot.img` for Samsung ODIN firmware
- [MagiskInit] Support replacing existing \*.rc files in `overlay.d`
- [MagiskInit] Rewrite sepolicy.rules mounting and loading implementation
