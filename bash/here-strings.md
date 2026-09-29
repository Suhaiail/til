# Here strings

> Learned: 2026-09-29

Use `<<<` to pass a string as stdin: `grep 'pattern' <<< "$variable"` — no need for `echo | grep`.
