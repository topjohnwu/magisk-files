## Magisk (43c1105d) (22004)

- Rewrite logfile writer from scratch, should resolve any crashes and deadlock

## Diffs to v22.0

- [App] Prevent multiple installation sessions running in parallel
- [App] Prevent OutOfMemory crashes when checking boot signature on PXA boot images
- [General] Proper cgroup migration implementation
- [General] Rewrite log writer from scratch, should resolve any crashes and deadlock
- [MagiskBoot] Preserve and patch AVB 2.0 structures/headers in boot images
