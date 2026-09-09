# Trap signals

> Learned: 2026-09-09

`trap 'cleanup_function' EXIT` ensures cleanup runs even if the script crashes or is interrupted with Ctrl+C.
