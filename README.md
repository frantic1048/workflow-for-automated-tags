## Repository Configuration

- `secrets.GH_PAT`: A Personal Access Token with _read and write_ access to the `Content` scope.

## How workflows runs

1. User: push a commit with message start with `[release]`
2. Workflow(on branch push): runs, push a new commit with a tag, authenticated with a Personal Access Token
3. Workflow(on branch push) and Workflow(on tag push): runs
