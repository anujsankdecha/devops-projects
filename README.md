# devops-project

Simple demo DevOps project used to show Git workflows.

## Branching model
- `main` — production-ready releases
- `dev` — integration branch for merged features
- `feature/*` — short-lived feature branches from `dev`

## How to run (local)
1. Clone: `git clone https://github.com/anujsankdecha/devops-project.git`
2. Work on feature branch: `git checkout -b feature/my-feature dev`

## Contributing
- Create `feature/*` branch from `dev`
- Open PR to `dev` and request review
- After tests & approval, merge into `dev`
- When stable, open PR `dev` → `main` for release

## Contact
- Owner: anujsankdecha
