# Restrictions

## Success Criteria

<!-- The evaluator scores each iteration against these. Mark each as (hard) or (soft). -->

- [ ] (hard) Runs without errors
- [ ] (hard) Core functionality works as described in Goal
- [ ] (soft) Has type hints on all function signatures
- [ ] (soft) Functions are under 30 lines
- [ ] (soft) Includes usage examples or help text

## Hard Constraints

<!-- MUST pass. A single failure means the iteration fails. -->

- Must run without errors on the target platform
- No dependencies beyond those listed in Context

## Soft Constraints

<!-- Scored. Meeting more raises the score. Failing one doesn't block the iteration. -->

- Has docstrings on public functions
- Handles edge cases gracefully (no crashes on bad input)
- Output is well-formatted and readable

## Out of Scope

- Do not modify files outside the declared scope
- Do not modify any files inside the specs/ directory
- Do not install dependencies without listing them in the output
- Do not make network requests unless the program explicitly allows it
