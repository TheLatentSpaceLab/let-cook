---
name: start-project
description: Scaffold a new autonomous loop project. Copies specs/PROGRAM.md, specs/RESTRICTIONS.md, and specs/SKILL.md into the target directory so the user can define the task and run /start-working.
argument-hint: [path/to/directory]
---

Initialize an autonomous loop project in `$ARGUMENTS` (or the current directory if no argument given).

## Steps

1. Determine the target directory from `$ARGUMENTS` (default: `.`).
2. Create the target directory if it doesn't exist.
3. Copy the following files into the target directory's `specs/` subdirectory **only if they don't already exist** (never overwrite):
   - `specs/PROGRAM.md` — from the template below
   - `specs/RESTRICTIONS.md` — from the template below
   - `specs/SKILL.md` — the execution engine

4. Print a summary of what was created and the next steps.

## Templates

### specs/PROGRAM.md

!`cat templates/PROGRAM.md`

### specs/RESTRICTIONS.md

!`cat templates/RESTRICTIONS.md`

### specs/SKILL.md

!`cat SKILL.md`
