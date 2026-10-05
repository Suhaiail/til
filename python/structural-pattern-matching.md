# Structural pattern matching

> Learned: 2026-10-05

Python 3.10+ supports `match`/`case` statements for clean pattern matching:
```python
match command:
    case 'quit': exit()
    case 'hello': print('Hi!')
```
