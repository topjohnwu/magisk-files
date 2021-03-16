## Magisk (f152b4c2) (22005)

- [General] Fix log writer implementation (yet again!)
- [MagiskInit] Fix `sepolicy.rule` mounting strategy
- [App] Cleanup fragment navigations
- [MagiskBoot] Properly strip out data encryption flags

## Diffs to v22.0

- [App] Prevent multiple installation sessions running in parallel
- [App] Prevent OutOfMemory crashes when checking boot signature on PXA boot images
- [General] Proper cgroup migration implementation
- [General] Rewrite log writer from scratch, should resolve any crashes and deadlock
- [MagiskBoot] Preserve and patch AVB 2.0 structures/headers in boot images
- [MagiskBoot] Properly strip out data encryption flags
- [MagiskInit] Fix `sepolicy.rule` mounting strategy
