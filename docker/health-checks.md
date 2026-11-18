# Health checks

> Learned: 2026-11-18

Add `HEALTHCHECK CMD curl -f http://localhost/ || exit 1` to your Dockerfile so Docker knows when a container is unhealthy.
