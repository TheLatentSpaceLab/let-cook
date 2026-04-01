# Autonomous Loop

When the user asks to **start a project** or scaffold a new task:

1. Read `specs/SKILL.md` if it exists in the current directory. If not, tell the user to run the init script first.
2. Create `specs/PROGRAM.md` and `specs/RESTRICTIONS.md` from templates if they don't exist.
3. Tell the user to fill them in.

When the user asks to **start working** or run the loop:

1. Read `specs/SKILL.md` — this is the execution engine. Follow it exactly.
2. Read `specs/PROGRAM.md` — this defines the task.
3. Read `specs/RESTRICTIONS.md` — this defines the quality gates.
4. Execute the autonomous loop as defined in `specs/SKILL.md`.
5. Never stop to ask for confirmation. Run autonomously until done.
