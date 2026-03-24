# Contributing

Thank you for your interest in contributing. By participating, you agree to follow this repository’s [**CODE_OF_CONDUCT.md**](CODE_OF_CONDUCT.md).

## Workflow

1. **Fork** this repository and create a branch from `main` (suggested names: `feature/…`, `fix/…`).
2. After installing dependencies locally, ensure **proxy** and **dashboard** pass `type-check` and `lint`, and **router** passes `ruff` and `mypy --strict` (see “Development & Health Checks” in [README.md](README.md)).
3. Write **clear commit messages** that describe what changed and why.
4. Open a **Pull Request** against `main`. If there is a related issue, reference it in the description (e.g. `Fixes #123`).

## Code & compliance

- **TypeScript**: strict mode. **Python**: type annotations consistent with `mypy --strict`.
- **Do not** commit real API keys, secrets, production connection strings, identifiable personal data, or internal-only addresses.
- **Dependencies**: When adding a dependency, confirm its license is compatible with this project’s **MIT** license. If you introduce copyleft or strongly restrictive licenses, discuss in an Issue first.
- **Cross-service changes**: Review contracts under `contracts/` and avoid breaking HTTP API expectations.

## Intellectual property

- Code you submit is licensed under the **same license as this repository** (see [LICENSE](LICENSE)), unless you clearly state otherwise. If you include third-party code, document its source and license.
- If you do not agree to license your contribution under the MIT terms, please do not open a PR.

## Code of Conduct

For interactions in Issues, PRs, and reviews, follow [**CODE_OF_CONDUCT.md**](CODE_OF_CONDUCT.md). For harassment or abuse, use the contact paths in [SECURITY.md](SECURITY.md). For general (non-security) matters, use [Issues](https://github.com/Moonaria123/smart-router-butler/issues) or other channels maintainers have published.
