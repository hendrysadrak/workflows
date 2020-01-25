# Github Actions Workflows

Collection of Github Actions workflows

## Create Github release with commit history as details

[create-release.yml](/create-release.yml)

On pushing a tag creates GitHub release and adds commit history as the details in format of:

```md
## Commits

- 2a0a657 commit message - committer name
- 464d8ff commit message - committer name
```

