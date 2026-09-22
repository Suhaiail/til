# Multi-stage builds

> Learned: 2026-09-22

Use multiple `FROM` statements in a Dockerfile to keep the final image small — build in one stage, copy only the binary to a minimal base image.
