# Changelog

## 0.1.0 (2026-04-03)

- Initial release
- Path handling with normalization, component iteration, join, parent
- Mount table with longest-prefix match and read-only support
- POSIX-like file operations (open, read, write, seek, close, stat)
- Directory operations (readdir, mkdir, rmdir)
- Filesystem trait for pluggable filesystem implementations
- Block device trait with GPT and MBR partition table parsing
- Top-level VFS with working directory tracking
