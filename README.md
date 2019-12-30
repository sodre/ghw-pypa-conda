# Helpful GitHub Workflows

## Usage
The easiest way to "copy" a workflow into your own package is as follows:
  - Add sodre/workflows as a remote
    `hub remote add sodre/workflows ghw-sodre
  - Fetch the latest
    `hub fetch --all`
  - Copy the workflow that you want to use
    `git show ghw-sodre/master:pypa-conda.yaml > .github/workflows/pypa-conda.yaml`

