# Walrus operator

> Learned: 2026-10-22

The walrus operator `:=` lets you assign and test in one expression:
```python
if (n := len(items)) > 10:
    print(f'Too many: {n}')
```
