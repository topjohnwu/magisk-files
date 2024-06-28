## Magisk (45fa1fce) (27003)

- [General] Support 16k page size
- [MagiskPolicy] Preserve sepolicy config flag after patching
- [MagiskPolicy] Optimize patching rules to reduce the amount of new rules injected
- [Core] Remove unnecessary mirror for magic mount
- [DenyList] Support enforcing denylist when Zygisk is disabled
- [Resetprop] Improve implementation to workaround several property modification detections
- [Resetprop] Update to properly work with property overlays

## Diffs to v27.0

- [General] Use a minimal libc to build static executables (`magiskinit` and `magiskboot`) for smaller sizes
- [MagiskInit] Rewrite 2SI logic for injecting `magiskinit` as `init`
- [MagiskBoot] Support spliting kernel images without decompression
- [App] Support patching Samsung firmware with images larger than 8GiB
- [App] Use user-initiated job instead of foreground services on Android 14
