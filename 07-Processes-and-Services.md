# 07. Processes & services

Beginner reference: command, purpose, and a simple example. Examples should be adapted to your own machine or authorized lab.

| # | Command | Purpose | Example |
|---:|---|---|---|
| 1 | `ps` | Show processes associated with the current terminal. | `ps` |
| 2 | `ps aux` | Show processes across the system. | `ps aux` |
| 3 | `top` | Monitor processes and system resources live. | `top` |
| 4 | `htop` | Interactive process viewer, if installed. | `htop` |
| 5 | `pgrep name` | Find process IDs by name. | `pgrep firefox` |
| 6 | `pidof program` | Show the process ID of a running program. | `pidof ssh` |
| 7 | `kill PID` | Send the default termination signal to a process you own or administer. | `kill 1234` |
| 8 | `kill -TERM PID` | Request graceful process termination. | `kill -TERM 1234` |
| 9 | `jobs` | List jobs in the current shell. | `jobs` |
| 10 | `bg` | Resume a suspended job in the background. | `bg` |
| 11 | `fg` | Bring a shell job to the foreground. | `fg` |
| 12 | `systemctl status service` | Check a service's status. | `systemctl status ssh` |
| 13 | `systemctl start service` | Start a service (admin task). | `sudo systemctl start ssh` |
| 14 | `systemctl stop service` | Stop a service (admin task). | `sudo systemctl stop ssh` |
| 15 | `systemctl enable service` | Enable a service at startup (admin task). | `sudo systemctl enable ssh` |

[← Back to README](README.md)
