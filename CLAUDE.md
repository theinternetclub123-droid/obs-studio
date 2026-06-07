# Claude Code Instructions

## Branching
- Always push directly to `master`. Do not create new branches.
- If you are on a different branch, merge into master and push.

## Building
- This project builds with CMake using the `windows-x64-local` preset.
- Always set `CMAKE_TLS_VERIFY=0` when downloading dependencies.
