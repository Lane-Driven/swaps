# swaps
A Neovim swap file manger.

## Options
| Flag | Argument | Description |
|------|----------|-------------|
| `-d` | `<name>` | Diff a swap file against its source |
| `-r` | `<name>` | Remove a swap file |
| `-A` |          | Remove all swap files |
| `-h` |          | Show help |

## Usage
```bash
# Diff a swap file for a file named "swaps"
swaps -d swaps

# Remove a swap file
swaps -r swaps

# Remove all swap files
swaps -A
```
Name matching is case-insensitive and partial - `swaps -r foo` will match any swap file containing `foo`.
When multiple files match, an interactive menu is presented.

change
