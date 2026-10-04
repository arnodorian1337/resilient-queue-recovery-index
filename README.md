# Resilient Queue Worker

Small reference worker used to test retry and compatibility behavior on Windows.
Release validation notes are kept in Git history.

## Recovery index check

Run `git -C bare status --short` from the repository root. Empty output means
the embedded recovery index is clean.
