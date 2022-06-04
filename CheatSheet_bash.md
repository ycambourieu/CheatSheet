
# Bash CheatSheet
Bash commands that make your life better.

### Adapt the command output to the console size
```bash
your_command | cut -c -$(tput cols)
```

### Enable timestamp display into the history file 
```bash
export HISTTIMEFORMAT="%Y-%m-%d %T "
```

### Display results nicely into column with a custom separator
```bash
your_command | column -t -s "="
```