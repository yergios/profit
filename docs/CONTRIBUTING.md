# Contributing guidelines

## Project structure

```
src/
├── index.html     # main page
├── css/styles.css # styles (normalize.css applied, app styles pending)
└── js/app.js      # app logic
docs/
├── assets/        # mockup images
├── CONTRIBUTING.md
└── mockup.md
```

## Workflow rules

- No direct pushes to main branch. All changes go through PRs that need at least 1 approval.
- Branch naming: `<label>/<issue-number>-description`, e.g. `feature/123-add-cost-row`.

## Formatting rules

- Indentation: 2 spaces
- File naming: kebab-case
- Commit messages: [Conventional commits](https://www.conventionalcommits.org/en/v1.0.0/#summary)
