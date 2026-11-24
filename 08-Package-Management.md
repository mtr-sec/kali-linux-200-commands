# 08. Package management (APT)

Beginner reference: command, purpose, and a simple example. Examples should be adapted to your own machine or authorized lab.

| # | Command | Purpose | Example |
|---:|---|---|---|
| 1 | `sudo apt update` | Refresh package lists. | `sudo apt update` |
| 2 | `sudo apt upgrade` | Upgrade installed packages. | `sudo apt upgrade` |
| 3 | `sudo apt full-upgrade` | Perform a full upgrade, resolving package changes. | `sudo apt full-upgrade` |
| 4 | `apt search keyword` | Search available packages. | `apt search wireshark` |
| 5 | `apt show package` | Display package information. | `apt show curl` |
| 6 | `sudo apt install package` | Install a package from configured repositories. | `sudo apt install tree` |
| 7 | `sudo apt remove package` | Remove an installed package. | `sudo apt remove tree` |
| 8 | `sudo apt purge package` | Remove a package and its system configuration files. | `sudo apt purge tree` |
| 9 | `sudo apt autoremove` | Remove automatically installed packages no longer needed. | `sudo apt autoremove` |
| 10 | `dpkg -l` | List installed Debian packages. | `dpkg -l` |
| 11 | `dpkg -S /path/file` | Find which installed package owns a file. | `dpkg -S /usr/bin/curl` |
| 12 | `apt list --installed` | List installed packages. | `apt list --installed` |

[← Back to README](README.md)
