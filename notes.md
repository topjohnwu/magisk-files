## Magisk (9968af07) (24103)

- [MagiskBoot] Support `lz4_legacy` archive with multiple magic
- [MagiskBoot] Fix `lz4_lg` compression
- [Zygisk] Fix application UID tracking
- [Zygisk] Fix improper `umask` being set in zygote
- [MagiskSU] Fix command logging when using `su -c <cmd>`
- [MagiskSU] Prevent su request indefinite blocking
- [App] Major app upgrade flow improvements
- [General] Improve commandline error handling and messaging

## Diffs to v24.1

- [MagiskSU] Fix buffer overflow
- [MagiskSU] Fix owner managed multiuser superuser settings
- [MagiskSU] Fix command logging when using `su -c <cmd>`
- [MagiskSU] Prevent su request indefinite blocking
- [MagiskBoot] Support `lz4_legacy` archive with multiple magic
- [MagiskBoot] Fix `lz4_lg` compression
- [DenyList] Allow targeting processes running as system UID
- [Zygisk] Workaround Samsung's "early zygote"
- [Zygisk] Improved Zygisk loading mechanism
- [Zygisk] Fix application UID tracking
- [Zygisk] Fix improper `umask` being set in zygote
- [App] Fix BusyBox execution test
- [App] Improve stub loading mechanism
- [App] Major app upgrade flow improvements
- [General] Improve commandline error handling and messaging
