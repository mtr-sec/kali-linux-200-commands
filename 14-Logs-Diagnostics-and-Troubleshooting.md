# 14. Logs, diagnostics & troubleshooting

Beginner reference: command, purpose, and a simple example. Examples should be adapted to your own machine or authorized lab.

| # | Command | Purpose | Example |
|---:|---|---|---|
| 1 | `journalctl` | Read the systemd journal. | `journalctl` |
| 2 | `journalctl -p err` | Show error-priority journal entries. | `journalctl -p err` |
| 3 | `journalctl -u service` | Show logs for a specific service. | `journalctl -u NetworkManager` |
| 4 | `dmesg -T` | Show kernel messages with readable timestamps. | `dmesg -T` |
| 5 | `systemctl --failed` | List failed systemd units. | `systemctl --failed` |
| 6 | `uptime` | Check system uptime and load averages. | `uptime` |
| 7 | `free -h` | Check available memory. | `free -h` |
| 8 | `df -h` | Check available disk space. | `df -h` |
| 9 | `vmstat 1 5` | Show system performance statistics five times. | `vmstat 1 5` |
| 10 | `iostat` | Show CPU and I/O statistics, if sysstat is installed. | `iostat` |
| 11 | `lsof` | List open files and the processes using them. | `sudo lsof` |
| 12 | `strace command` | Trace system calls made by a program (advanced diagnostics). | `strace ls` |

[← Back to README](README.md)
