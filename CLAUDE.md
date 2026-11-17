# Contribution rules

- PR titles must follow [Conventional Commits](https://www.conventionalcommits.org/): `<type>: <description>`, e.g. `feat: add pricing section`, `fix: correct mobile nav overflow`. Allowed types: `feat`, `fix`, `chore`, `docs`, `style`, `refactor`, `perf`, `test`, `build`, `ci`, `revert`. Enforced by `.github/workflows/pr-title-check.yml`.
- PRs require at least 2 approving reviews before merging (branch protection on `main`).

## Git

Follow `docs/git-protocol.md` in syntrak-home, the parent folder (`../docs/git-protocol.md`, or https://github.com/Syntraksoftware/syntrak-home): `type(scope): what changed`, `type/short-desc` branches, squash-merged PRs whose title is checked in CI. Scope for this repo: `web`. Never push or merge without the owner's yes.
