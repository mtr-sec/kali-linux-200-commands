# 02. Files & directories

Beginner reference: command, purpose, and a simple example. Examples should be adapted to your own machine or authorized lab.

| # | Command | Purpose | Example |
|---:|---|---|---|
| 1 | `mkdir folder` | Create a directory. | `mkdir projects` |
| 2 | `mkdir -p a/b` | Create parent directories as needed. | `mkdir -p projects/notes` |
| 3 | `touch file` | Create an empty file or update its timestamp. | `touch notes.txt` |
| 4 | `cp source dest` | Copy a file. | `cp notes.txt notes-backup.txt` |
| 5 | `cp -r source dest` | Copy a directory and its contents. | `cp -r project project-copy` |
| 6 | `mv source dest` | Move or rename a file or directory. | `mv draft.txt final.txt` |
| 7 | `rm file` | Remove a file. Check the path before running. | `rm old-notes.txt` |
| 8 | `rmdir folder` | Remove an empty directory. | `rmdir empty-folder` |
| 9 | `file name` | Identify a file's type. | `file document.pdf` |
| 10 | `stat file` | Show detailed file metadata. | `stat notes.txt` |
| 11 | `basename path` | Print the final component of a path. | `basename /home/kali/notes.txt` |
| 12 | `dirname path` | Print the directory component of a path. | `dirname /home/kali/notes.txt` |
| 13 | `realpath path` | Display an absolute resolved path. | `realpath notes.txt` |
| 14 | `find path -name pattern` | Find files by name. | `find ~/Documents -name '*.pdf'` |
| 15 | `locate filename` | Search an indexed file database, if available. | `locate notes.txt` |

[← Back to README](README.md)
