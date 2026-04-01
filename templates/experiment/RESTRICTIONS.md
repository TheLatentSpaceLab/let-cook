# Restrictions

## Success Criteria

<!-- The evaluator scores each iteration against these. Mark each as (hard) or (soft). -->

- [ ] (hard) Experiment runs to completion without errors
- [ ] (hard) Results are logged with metrics and timestamps
- [ ] (soft) Metrics improve over baseline across iterations
- [ ] (soft) Methodology is documented and reproducible
- [ ] (soft) Includes visualizations or summary tables

## Hard Constraints

<!-- MUST pass. A single failure means the iteration fails. -->

- All experiments must be reproducible (log seeds, versions, parameters)
- Results must not be cherry-picked — report all runs
- Must not modify input datasets

## Soft Constraints

<!-- Scored. Meeting more raises the score. Failing one doesn't block the iteration. -->

- Includes error bars or confidence intervals where applicable
- Compares against at least one baseline
- Code is clean enough for a colleague to re-run

## Out of Scope

- Do not modify files outside the declared scope
- Do not modify any files inside the specs/ directory
- Do not train models beyond the specified compute budget
- Do not download datasets larger than what is specified in Context
