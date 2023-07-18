## Magisk (d390ca2f) (26104)

Lots of code is migrated over to Rust!

- [App] Properly preserve `boot.img` when patching Samsung firmware with `init_boot.img`
- [MagiskBoot] Directly handle AVB 1.0 signing and verification without going through Java implementation

## Diffs to v26.1

- [MagiskBoot] Support extracting boot image from `payload.bin`
- [MagiskBoot] Support cpio files containing character files
- [MagiskBoot] Support listing cpio content
- [MagiskBoot] Directly handle AVB 1.0 signing and verification without going through Java implementation
- [Daemon] Make daemon socket a fixed path in MAGISKTMP
- [resetprop] Support printing property context
- [resetprop] Support only printing persistent properties from storage
- [resetprop] Properly support setting persistent properties bypassing property_service
- [MagiskSU] Support `-g` and `-G` options
- [MagiskSU] Support switching mount namespace to PID with `-t`
- [App] Support patching boot image from ROM zips
- [App] Properly preserve `boot.img` when patching Samsung firmware with `init_boot.img`
