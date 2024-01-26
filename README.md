# `tmux` Commands Cheat Sheat

A quick reference for commonly used `tmux` commands.

## Table of Contents

- [Starting and Attaching to Sessions](#starting-and-attaching-to-sessions)
- [Managing Windows](#managing-windows)
- [Splitting Panes](#splitting-panes)
- [Detaching and Exiting](#detaching-and-exiting)
- [Miscellaneous Commands](#miscellaneous-commands)

## Starting and Attaching to Sessions

| commands                                | Description                           |
|-----------------------------------------|---------------------------------------|
| `tmux`                                  | Start a new `tmux` session.           |
| `tmux new-session -s session_name`      | Start a new named `tmux` session      |
| `tmux attach-session -t session_name`   | Attach to an existing `tmux` session. |
| `tmux list-sessions`                    | List all `tmux` sessions.             |


## Managing Windows

| Command          | Description                                     |
|------------------|-------------------------------------------------|
| `Ctrl-b c`       | Create a new window.                            |
| `Ctrl-b ,`       | Rename the current window.                      |
| `Ctrl-b n`       | Switch to the next window.                      |
| `Ctrl-b p`       | Switch to the previous window.                  |
| `Ctrl-b 0-9`     | Switch to windows 0-9.                          |
| `Ctrl-b w`       | List windows and switch to the selected one.    |
| `Ctrl-b &`       | Close the current window (prompt for confirmation).|


## Splitting Panes

| Command       | Description                                |
|---------------|--------------------------------------------|
| `Ctrl-b %`    | Split the current pane vertically.         |
| `Ctrl-b "`    | Split the current pane horizontally.       |
| `Ctrl-b x`    | Close the current pane.                    |


## Detaching and Exiting

| Command                  | Description                                |
|--------------------------|--------------------------------------------|
| `Ctrl-b d`               | Detach from the `tmux` session.            |
| `tmux attach-session -d` | Reattach to a detached `tmux` session.     |


## Miscellaneous Commands

| Command                        | Description                                    |
|--------------------------------|------------------------------------------------|
| `tmux kill-session -t session_name` | Kill a `tmux` session by name.            |
| `Ctrl-b ?`                     | Display a list of all `tmux` commands.         |
| `Ctrl-b :`                     | Enter command mode to type `tmux` commands.    |

Feel free to explore more `tmux` commands.
for additional information, refer to the `tmux` man page (`man tmux`).
