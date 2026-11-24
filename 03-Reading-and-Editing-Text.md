# 03. Reading & editing text

Beginner reference: command, purpose, and a simple example. Examples should be adapted to your own machine or authorized lab.

| # | Command | Purpose | Example |
|---:|---|---|---|
| 1 | `cat file` | Print a file's contents. | `cat notes.txt` |
| 2 | `less file` | Read a file page by page. | `less /var/log/syslog` |
| 3 | `more file` | Read text one screen at a time. | `more notes.txt` |
| 4 | `head file` | Show the first 10 lines. | `head notes.txt` |
| 5 | `head -n 20 file` | Show the first 20 lines. | `head -n 20 notes.txt` |
| 6 | `tail file` | Show the last 10 lines. | `tail notes.txt` |
| 7 | `tail -f file` | Follow new lines added to a log file. | `tail -f app.log` |
| 8 | `wc file` | Count lines, words, and bytes. | `wc notes.txt` |
| 9 | `wc -l file` | Count lines only. | `wc -l notes.txt` |
| 10 | `sort file` | Sort lines alphabetically. | `sort names.txt` |
| 11 | `uniq file` | Remove adjacent duplicate lines. | `sort names.txt \| uniq` |
| 12 | `cut -d',' -f1 file` | Extract a delimited field. | `cut -d',' -f1 users.csv` |
| 13 | `paste file1 file2` | Merge lines from files side by side. | `paste first.txt second.txt` |
| 14 | `grep 'text' file` | Find matching text in a file. | `grep 'error' app.log` |
| 15 | `grep -r 'text' dir` | Search recursively in a directory. | `grep -r 'TODO' ./project` |
| 16 | `sed 's/old/new/' file` | Replace the first match on each line in output. | `sed 's/draft/final/' notes.txt` |
| 17 | `awk '{print $1}' file` | Print the first whitespace-separated field. | `awk '{print $1}' names.txt` |
| 18 | `tee file` | Write command output to a file and the terminal. | `printf 'Hello\n' \| tee hello.txt` |
| 19 | `nano file` | Open a beginner-friendly terminal text editor. | `nano notes.txt` |
| 20 | `vim file` | Open the Vim text editor. | `vim notes.txt` |

[← Back to README](README.md)
