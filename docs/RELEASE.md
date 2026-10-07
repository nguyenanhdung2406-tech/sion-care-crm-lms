# Release Process

## Normal change

`feature branch -> local test -> pull request -> review -> main -> GitHub Pages`

## Versioning

Use semantic versioning:
- PATCH: bug fix
- MINOR: backward-compatible feature
- MAJOR: breaking architecture/workflow change

Update `VERSION` and `CHANGELOG.md` for every release.

## Emergency rollback

Re-deploy the last known-good commit from `main`.