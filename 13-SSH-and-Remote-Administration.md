# 13. SSH & remote administration

Beginner reference: command, purpose, and a simple example. Examples should be adapted to your own machine or authorized lab.

| # | Command | Purpose | Example |
|---:|---|---|---|
| 1 | `ssh user@host` | Connect to a remote system you are authorized to access. | `ssh kali@192.0.2.10` |
| 2 | `ssh -V` | Display the SSH client version. | `ssh -V` |
| 3 | `ssh-keygen` | Create an SSH key pair. | `ssh-keygen -t ed25519` |
| 4 | `ssh-add -l` | List identities loaded in the SSH agent. | `ssh-add -l` |
| 5 | `scp file user@host:path` | Copy a file to an authorized remote host. | `scp notes.txt kali@192.0.2.10:~/` |
| 6 | `sftp user@host` | Open an interactive secure file-transfer session. | `sftp kali@192.0.2.10` |
| 7 | `sshd -t` | Check SSH server configuration syntax. | `sudo sshd -t` |

[← Back to README](README.md)
