# 04. Permissions & ownership

Beginner reference: command, purpose, and a simple example. Examples should be adapted to your own machine or authorized lab.

| # | Command | Purpose | Example |
|---:|---|---|---|
| 1 | `ls -l` | Inspect permissions and ownership. | `ls -l notes.txt` |
| 2 | `chmod 644 file` | Set owner read/write and others read permissions. | `chmod 644 notes.txt` |
| 3 | `chmod +x script` | Make a script executable. | `chmod +x script.sh` |
| 4 | `chmod -x script` | Remove execute permission. | `chmod -x script.sh` |
| 5 | `chown user file` | Change a file's owner (requires permission). | `sudo chown kali notes.txt` |
| 6 | `chgrp group file` | Change a file's group. | `sudo chgrp users notes.txt` |
| 7 | `umask` | Display the default permission mask. | `umask` |
| 8 | `umask 022` | Set a common default permission mask for the current shell. | `umask 022` |
| 9 | `getfacl file` | Display access-control-list permissions. | `getfacl notes.txt` |
| 10 | `setfacl -m u:user:r file` | Grant a user read access using an ACL. | `setfacl -m u:kali:r notes.txt` |

[← Back to README](README.md)
