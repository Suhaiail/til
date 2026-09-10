# Window functions

> Learned: 2026-09-10

Use `ROW_NUMBER() OVER (PARTITION BY dept ORDER BY salary DESC)` to rank employees within each department without subqueries.
