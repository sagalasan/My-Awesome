# My Awesome

## Table of Contents
1. [Git](#git)

### Git <a name="git"></a>

- Find lost stashes or dangling commits
```bash
gitk --all $( git fsck --no-reflog | awk '/dangling commit/ {print $3}' )
```
