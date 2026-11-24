# 06. System information & hardware

Beginner reference: command, purpose, and a simple example. Examples should be adapted to your own machine or authorized lab.

| # | Command | Purpose | Example |
|---:|---|---|---|
| 1 | `uname -a` | Show kernel and system information. | `uname -a` |
| 2 | `uname -r` | Show the kernel release. | `uname -r` |
| 3 | `cat /etc/os-release` | Show Linux distribution details. | `cat /etc/os-release` |
| 4 | `hostnamectl` | Show or manage hostname and OS information. | `hostnamectl` |
| 5 | `uptime` | Show how long the system has been running. | `uptime` |
| 6 | `free -h` | Show memory usage. | `free -h` |
| 7 | `lscpu` | Show CPU architecture and details. | `lscpu` |
| 8 | `lsmem` | Show memory range information. | `lsmem` |
| 9 | `lsblk` | List block devices and partitions. | `lsblk` |
| 10 | `lspci` | List PCI devices. | `lspci` |
| 11 | `lsusb` | List USB devices. | `lsusb` |
| 12 | `lshw -short` | Show a concise hardware inventory (may require sudo). | `sudo lshw -short` |
| 13 | `dmidecode` | Read hardware/firmware information (admin privileges often needed). | `sudo dmidecode -t system` |
| 14 | `dmesg` | Display kernel ring-buffer messages. | `dmesg \| less` |
| 15 | `journalctl -b` | Show logs from the current boot. | `journalctl -b` |

[← Back to README](README.md)
