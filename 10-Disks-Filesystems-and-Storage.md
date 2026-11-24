# 10. Disks, filesystems & storage

Beginner reference: command, purpose, and a simple example. Examples should be adapted to your own machine or authorized lab.

| # | Command | Purpose | Example |
|---:|---|---|---|
| 1 | `df -h` | Show filesystem free and used space. | `df -h` |
| 2 | `du -sh folder` | Show a directory's total size. | `du -sh ~/Downloads` |
| 3 | `du -h --max-depth=1` | Show sizes of immediate subdirectories. | `du -h --max-depth=1 ~/` |
| 4 | `mount` | Display mounted filesystems. | `mount` |
| 5 | `findmnt` | Show mounted filesystems in a tree. | `findmnt` |
| 6 | `lsblk -f` | Show block devices with filesystem information. | `lsblk -f` |
| 7 | `blkid` | Display block-device attributes. | `sudo blkid` |
| 8 | `fdisk -l` | List partition tables (read-only listing). | `sudo fdisk -l` |
| 9 | `sync` | Flush filesystem buffers to storage. | `sync` |
| 10 | `free -h` | Check memory and swap usage. | `free -h` |

[← Back to README](README.md)
