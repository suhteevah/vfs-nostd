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

---

---

## Support This Project

If you find this project useful, consider buying me a coffee! Your support helps me keep building and sharing open-source tools.

[![Donate via PayPal](https://img.shields.io/badge/Donate-PayPal-blue.svg?logo=paypal)](https://www.paypal.me/baal_hosting)

**PayPal:** [baal_hosting@live.com](https://paypal.me/baal_hosting)

Every donation, no matter how small, is greatly appreciated and motivates continued development. Thank you!
