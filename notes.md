## Magisk (9c0e1897) (22007)

- [General] Fix logic to copy `sepolicy.rule` during module installation
- [resetprop] Always delete existing `ro.` props before updating. This will fix bootloops that could be caused by modifying device fingerprint properties.

## Diffs to v22.0

- [App] Prevent multiple installation sessions running in parallel
- [App] Prevent OutOfMemory crashes when checking boot signature on PXA boot images
- [General] Proper cgroup migration implementation
- [General] Rewrite log writer from scratch, should resolve any crashes and deadlock
- [General] Many scripts updates fixing regressions
- [MagiskHide] Prevent possible deadlock when signal arrives
- [MagiskHide] Partial match process names if necessary
- [MagiskBoot] Preserve and patch AVB 2.0 structures/headers in boot images
- [MagiskBoot] Properly strip out data encryption flags
- [MagiskBoot] Prevent possible integer overflow
- [MagiskInit] Fix `sepolicy.rule` mounting strategy
- [resetprop] Always delete existing `ro.` props before updating. This will fix bootloops that could be caused by modifying device fingerprint properties.
