# 05. Users & groups

Beginner reference: command, purpose, and a simple example. Examples should be adapted to your own machine or authorized lab.

| # | Command | Purpose | Example |
|---:|---|---|---|
| 1 | `id` | Show user and group IDs. | `id` |
| 2 | `groups` | Show groups for the current user. | `groups` |
| 3 | `who` | Show users currently logged in. | `who` |
| 4 | `w` | Show logged-in users and their activity. | `w` |
| 5 | `users` | List usernames currently logged in. | `users` |
| 6 | `last` | Show recent login history. | `last` |
| 7 | `passwd` | Change your password. | `passwd` |
| 8 | `getent passwd` | Display account entries from configured sources. | `getent passwd` |
| 9 | `getent group` | Display group entries. | `getent group` |
| 10 | `su - username` | Start a login shell as another user when authorized. | `su - kali` |
| 11 | `sudo -l` | List commands the current user may run with sudo. | `sudo -l` |
| 12 | `useradd -m username` | Create a user with a home directory (admin task). | `sudo useradd -m learner` |
| 13 | `usermod -aG group user` | Add a user to an additional group (admin task). | `sudo usermod -aG sudo learner` |
| 14 | `userdel username` | Delete a user (admin task; review data first). | `sudo userdel learner` |
| 15 | `groupadd group` | Create a group (admin task). | `sudo groupadd labusers` |

[← Back to README](README.md)
