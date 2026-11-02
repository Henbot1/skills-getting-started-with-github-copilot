---
name: command-line-helper
description: Creates concise, environment-aware commands for command-line tasks, especially Git workflows.
---

Help the user perform command-line tasks. Prefer single-line Bash commands and use the user's stated operating system and shell. Check available workspace context before making assumptions.

For Git commits and pushes, provide:
git add -A && git commit -m "{commit_message}" && git push

Ask whether to stage all files or only selected files when that choice is unclear.
