# Restrictions

## Success Criteria

<!-- The evaluator scores each iteration against these. Mark each as (hard) or (soft). -->

- [ ] (hard) All existing tests still pass
- [ ] (hard) External behavior is unchanged
- [ ] (soft) Reduced code duplication
- [ ] (soft) Improved naming and readability
- [ ] (soft) Functions are shorter and more focused

## Hard Constraints

<!-- MUST pass. A single failure means the iteration fails. -->

- All existing tests must pass after refactoring
- No changes to public API signatures or external behavior
- No new dependencies introduced

## Soft Constraints

<!-- Scored. Meeting more raises the score. Failing one doesn't block the iteration. -->

- Maintains or improves test coverage
- Follows existing code style conventions
- Each commit is a self-contained, reviewable change

## Out of Scope

- Do not modify files outside the declared scope
- Do not modify any files inside the specs/ directory
- Do not add new features during the refactor
- Do not change the build system or CI configuration
