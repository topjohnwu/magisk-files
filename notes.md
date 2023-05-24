## Magisk (47d2d4e3) (26102)

- Implement all logging code in the project with Rust
- [MagiskBoot] Support extracting boot image from `payload.bin`
- [Daemon] Make daemon socket a fixed path in MAGISKTMP
- [resetprop] Support printing property context
- [resetprop] Support only printing persistent properties from storage
- [resetprop] Properly support setting persistent properties bypassing property_service
- [MagiskSU] Support `-g` and `-G` options
- [MagiskSU] Support switching mount namespace to PID with `-t`

## Diffs to v26.1

- [MagiskBoot] Support extracting boot image from `payload.bin`
- [Daemon] Make daemon socket a fixed path in MAGISKTMP
- [resetprop] Support printing property context
- [resetprop] Support only printing persistent properties from storage
- [resetprop] Properly support setting persistent properties bypassing property_service
- [MagiskSU] Support `-g` and `-G` options
- [MagiskSU] Support switching mount namespace to PID with `-t`
