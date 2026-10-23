# DevOps Labs

Lab work for the DevOps course, one folder per week.

| Week | Lab | Folder | CI |
|------|-----|--------|----|
| 03 | Lab 1 — CI/CD pipeline with GitHub Actions | [`week03/ci-cd-lab`](week03/ci-cd-lab) | [`week03-ci.yml`](.github/workflows/week03-ci.yml) |

GitHub Actions only reads workflows from `.github/workflows/` at the repository root, so each lab has its own workflow file there. Each workflow runs inside its lab folder and only triggers when that folder changes.
