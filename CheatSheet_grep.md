# Grep CheatSheet
Grep commands that make your life easier.

### Multiple research into a single grep
```bash
grep -e 'Condition1' -e 'Condition2'
grep -E "Condition1|Condition2"
```

### Research lines Before -B and After -A
```bash
grep -A 3 -B 1 'Researched' /your/file
```

### Research 2 lines before and after with -C
```bash
grep -C 2 'Researched' /your/file
```

### Display line numbers in results
```bash
grep -n
```

### List file with and without match
```bash
grep -l # Only matching files
grep -L # Only non matching files
```