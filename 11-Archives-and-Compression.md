# 11. Archives & compression

Beginner reference: command, purpose, and a simple example. Examples should be adapted to your own machine or authorized lab.

| # | Command | Purpose | Example |
|---:|---|---|---|
| 1 | `tar -czf archive.tar.gz folder` | Create a gzip-compressed tar archive. | `tar -czf backup.tar.gz Documents` |
| 2 | `tar -xzf archive.tar.gz` | Extract a gzip-compressed tar archive. | `tar -xzf backup.tar.gz` |
| 3 | `tar -tf archive.tar` | List archive contents without extracting. | `tar -tf backup.tar` |
| 4 | `zip -r archive.zip folder` | Create a ZIP archive. | `zip -r notes.zip notes/` |
| 5 | `unzip archive.zip` | Extract a ZIP archive. | `unzip notes.zip` |
| 6 | `gzip file` | Compress a file with gzip. | `gzip report.txt` |
| 7 | `gunzip file.gz` | Decompress a gzip file. | `gunzip report.txt.gz` |
| 8 | `bzip2 file` | Compress a file using bzip2. | `bzip2 report.txt` |
| 9 | `xz file` | Compress a file using xz. | `xz report.txt` |
| 10 | `7z a archive.7z folder` | Create a 7z archive, if p7zip is installed. | `7z a notes.7z notes/` |

[← Back to README](README.md)
