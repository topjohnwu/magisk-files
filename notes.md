## Magisk (a8c4a33e) (26103)

Lots of code is migrated over to Rust!

- [MagiskBoot] Support cpio files containing character files
- [MagiskBoot] Support listing cpio content
- [App] Support patching boot image from ROM zips

## Diffs to v26.1

- [MagiskBoot] Support extracting boot image from `payload.bin`
- [MagiskBoot] Support cpio files containing character files
- [MagiskBoot] Support listing cpio content
- [Daemon] Make daemon socket a fixed path in MAGISKTMP
- [resetprop] Support printing property context
- [resetprop] Support only printing persistent properties from storage
- [resetprop] Properly support setting persistent properties bypassing property_service
- [MagiskSU] Support `-g` and `-G` options
- [MagiskSU] Support switching mount namespace to PID with `-t`
- [App] Support patching boot image from ROM zips
