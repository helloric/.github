# HelloRic Student Project — Contributing

Welcome! This repository is maintained by the HelloRic student team. Follow these rules to contribute safely and consistently.

## Quick rules
- Use the issue tracker for bug reports and feature requests.
- We are using [GitHub Flow](https://docs.github.com/en/get-started/using-github/github-flow)
- Follow the [link](#branch--pr-workflow)
- If you want to contribute from outside the Org please fork&PR.
- Run tests and linters locally before pushing.

## Branch & PR workflow
1. Create an issue describing what should be implemented
1. Create branch from the issue
2. Create Draft PR from the branch
3. Work on the branch associated with the PR
4. Request review when finished.

## Commit messages
- Use imperative, short subject lines: "Add X", "Fix Y".
- Include a one-line subject (<= 72 chars) and optional body describing why.
- Example: feat: add robot calibration command

## Local development setup
- Document how to start the project locally (minimal instructions or link to README/devsetup).
- Include commands for common tasks:
  - Install deps: pip install -r requirements.txt
  - Run tests: pytest
- Ideally, implement a devcontainer for VS Code.

## Testing & verification
- Add unit/integration tests where applicable.
- Add manual tests where needed.
- Document your code and the manual tests.


## CI & quality gates
- PRs must pass CI (tests + linters) before merge.
- Add tests for bug fixes and new features where applicable.
- If a test is flaky, mark it and open an issue; do not remove without discussion.

## Labels
- Use labels: bug, enhancement, docs, help wanted...

## Security & sensitive data
- Do not commit secrets (API keys, tokens). Use environment variables or secret storage.
- For security vulnerabilities, contact maintainers directly.

## Contacts & support
- Maintainers: @brean, @adriandavidauer 


Thank you for contributing to HelloRic!