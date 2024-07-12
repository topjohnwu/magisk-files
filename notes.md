## Magisk (b38ab2a7) (27004)

- [General] Add support for RISC-V
- [App] Major internal code refactoring
- [App] Support Android 13+ built-in per-app language preferences

## Diffs to v27.0

- [General] Support 16k page size
- [General] Use a minimal libc to build static executables (`magiskinit` and `magiskboot`) for smaller sizes
- [Core] Remove unnecessary mirror for magic mount
- [MagiskInit] Rewrite 2SI logic for injecting `magiskinit` as `init`
- [MagiskPolicy] Preserve sepolicy config flag after patching
- [MagiskPolicy] Optimize patching rules to reduce the amount of new rules being injected
- [DenyList] Support enforcing denylist when Zygisk is disabled
- [Resetprop] Improve implementation to workaround several property modification detections
- [Resetprop] Update to properly work with property overlays
- [App] Support patching Samsung firmware with images larger than 8GiB
- [App] Use user-initiated job instead of foreground services on Android 14
- [MagiskBoot] Support spliting kernel images without decompression
