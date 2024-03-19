## Magisk (81658d45) (27002)

- [General] Use a minimal libc to build static executables (`magiskinit` and `magiskboot`) for smaller sizes
- [MagiskInit] Rewrite 2SI logic for injecting `magiskinit` as `init`
- [MagiskBoot] Support spliting kernel images without decompression
- [App] Support patching Samsung firmware with images larger than 8GiB
- [App] Use user-initiated job instead of foreground services on Android 14

## Diffs to v27.0
