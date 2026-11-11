# Context managers

> Learned: 2026-11-11

Use `contextlib.contextmanager` to write custom `with` blocks:
```python
@contextmanager
def timer():
    start = time.time()
    yield
    print(f'Elapsed: {time.time() - start:.2f}s')
```
