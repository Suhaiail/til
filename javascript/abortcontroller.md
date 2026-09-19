# AbortController

> Learned: 2026-09-19

Use `AbortController` to cancel fetch requests:
```javascript
const ctrl = new AbortController();
fetch(url, { signal: ctrl.signal });
ctrl.abort();
```
