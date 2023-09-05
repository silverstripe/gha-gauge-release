# GitHub Actions - Gauge release

GitHub action to gauge whether to do a patch release

Action is designed to only be used as part of [gha-ci](https://github.com/silverstripe/gha-ci) and [gha-action-ci](https://github.com/silverstripe/gha-action-ci)

## Inputs

### Latest local sha
Required - The result of $(git rev-parse HEAD)
`latest_local_sha: `f22dbc6ec6118096c8ccccee1ca0074bfb2f2291`
