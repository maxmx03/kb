This script provides a simple Kanban system using folders and Markdown files. It allows you to organize tasks into different stages of progress, such as `backlog`, `ready`, `inprogress`, `review`, and `done`.

```txt
kanban/
├── backlog/
├── ready/
├── inprogress/
├── review/
└── done/
```

## Installation

To install the script, add it your shell configuration

```bash
echo "source /path/to/kanban.sh" >> $HOME/.bashrc
```  

## Requirements

- [gum](https://github.com/charmbracelet/gum)

## Commands

```bash
# To display available commands
kb
```
