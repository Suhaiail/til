# Walrus operator

> Learned: 2026-09-16

The walrus operator `:=` lets you assign and test in one expression:
```python
if (n := len(items)) > 10:
    print(f'Too many: {n}')
```
