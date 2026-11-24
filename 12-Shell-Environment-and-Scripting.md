# 12. Shell, environment & scripting

Beginner reference: command, purpose, and a simple example. Examples should be adapted to your own machine or authorized lab.

| # | Command | Purpose | Example |
|---:|---|---|---|
| 1 | `echo text` | Print text to the terminal. | `echo 'Hello Kali'` |
| 2 | `printf format` | Print formatted text. | `printf 'Name: %s\n' 'Kali'` |
| 3 | `env` | Display environment variables. | `env` |
| 4 | `printenv HOME` | Display a selected environment variable. | `printenv HOME` |
| 5 | `export NAME=value` | Set an environment variable for this shell and child processes. | `export PROJECT=lab` |
| 6 | `which command` | Show the executable found in PATH. | `which python3` |
| 7 | `type command` | Describe how the shell interprets a command. | `type cd` |
| 8 | `command -v command` | Show how a command would be resolved. | `command -v python3` |
| 9 | `alias` | List shell aliases. | `alias` |
| 10 | `unalias name` | Remove a shell alias. | `unalias ll` |
| 11 | `source file` | Read and execute a shell file in the current shell. | `source ~/.bashrc` |
| 12 | `bash script.sh` | Run a script using Bash. | `bash hello.sh` |
| 13 | `sh script.sh` | Run a script using sh. | `sh script.sh` |
| 14 | `sleep 5` | Pause for five seconds. | `sleep 5` |
| 15 | `xargs` | Build command arguments from standard input. | `printf 'a\nb\n' \| xargs -n1 echo` |

[← Back to README](README.md)
