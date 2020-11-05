# awk

## Limit output of `ls` to only show certain columns

#### Syntax

`ls -l | awk '{print $5, $6, $7, $9}'`

#### Example

```
jin@encrypt /tmp/foo % ls -l
total 0
drwxr-xr-x  2 jin  wheel  68 Oct  4 12:43 bar
drwxr-xr-x  2 jin  wheel  68 Oct  4 12:43 baz
drwxr-xr-x  2 jin  wheel  68 Oct  4 12:43 quux

jin@encrypt /tmp/foo % ls -l | awk '{print $5, $6, $7, $9}'
68 Oct 4 bar
68 Oct 4 baz
68 Oct 4 quux
```
