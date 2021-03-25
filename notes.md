## Magisk (66e30a77) (22006)

- [App] Fix app crashing when download + install modules
- [MagiskHide] Prevent possible deadlock when signal arrives
- [MagiskHide] Partial match process names if necessary
- [MagiskHide] Don't include MicroG SafetyNet process by default
- [MagiskBoot] Prevent possible integer overflow
- [General] Many scripts updates fixing regressions

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
