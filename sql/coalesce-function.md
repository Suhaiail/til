# COALESCE function

> Learned: 2026-11-17

`COALESCE(a, b, c)` returns the first non-NULL value. Useful for providing defaults:
```sql
SELECT COALESCE(nickname, first_name, 'Anonymous') AS display_name FROM users;
```
