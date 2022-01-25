# Renovate Config

Renovate helps to keep dependencies up to date. It will periodically create Pull Requests to install new versions of any dependencies with updates. Renovate is fully configurable and developers can control its behavior in their repositories using the PRs it makes. Close a PR to have it ignore updates for that dependency, or leave it open if you want upgrade it later and Renovate will rebase the branch to keep it from getting stale.

## Usage

Create a `renovate.json` file in your repository, with the following content:

###### `renovate.json`

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": [
    "github>geerteltink/.github:renovate-config"
  ]
}
```

Review [full configuration docs](https://docs.renovatebot.com/configuration-options/).
