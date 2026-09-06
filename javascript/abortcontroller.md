# AbortController

> Learned: 2026-09-06

Use `AbortController` to cancel fetch requests:
```javascript
const ctrl = new AbortController();
fetch(url, { signal: ctrl.signal });
ctrl.abort();
```
