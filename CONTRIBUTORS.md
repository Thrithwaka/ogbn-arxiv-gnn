# Contributors

This project is maintained by a small team, with each contributor owning a
specific area of the pipeline.

| Name | GitHub | Focus Area |
|------|--------|------------|
| Aadhil | `@_add-username_` | Tensor operations & foundations |
| Thilani | `@_add-username_` | Graph analysis & data pipeline |
| Thrithwaka | `@_add-username_` | GNN model development |
| Navodya | `@_add-username_` | Training, optimization & evaluation |
| Kaveesha | `@_add-username_` | Explainability & dashboard |

Everyone on the team is expected to understand the full pipeline end to
end, not just their own area — component owners walk the rest of the team
through their work once it's merged.

## Workflow

1. Branch off `main`: `feature/<short-name>`
2. Commit using [Conventional Commits](https://www.conventionalcommits.org/)
   (`feat:`, `fix:`, `docs:`, `chore:`)
3. Open a Pull Request into `main`
4. Get at least one review/approval before merging
5. Update the roadmap checklist in `README.md`

## Working Norms

- Surface blockers early in the team channel rather than at the last minute
- Review teammates' PRs within 24 hours where possible
- Keep commits scoped to one logical change for a clean, reviewable history
- Log every training run's hyperparameters and results (W&B or
  `reports/experiment_log.md`) so nothing is lost or duplicated
