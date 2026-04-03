# vfs-nostd

`no_std` Virtual Filesystem layer with mount table and POSIX-like API in Rust.

## Features

- **Path handling**: Heap-allocated paths with normalization, component iteration, join, parent
- **Mount table**: Longest-prefix match, read-only flag, ordered mount listing
- **File ops**: POSIX-like open/read/write/seek/close/stat with file descriptors
- **Directory ops**: readdir, mkdir, rmdir, DirEntry
- **Filesystem trait**: Pluggable trait for ext4/btrfs/NTFS/FAT32 implementations
- **Block device**: Trait for storage backends + GPT/MBR partition parsing
- **VFS**: Unified API with working directory tracking

## License

Licensed under either of Apache License 2.0 or MIT License at your option.
