# Helpful GitHub Workflows

## Usage
The easiest way to "copy" a workflow into your own package is as follows:
  - Add sodre/workflows as a remote and fetch all branches
    ```bash
    git remote add ghw-sodre https://github.com/sodre/workflows.git
    git fetch --all
    ```
  - Copy the workflow that you want to use
    ```
    git show ghw-sodre/master:pypa-conda.yaml > .github/workflows/pypa-conda.yaml
    git add .github/workflows/pypa-conda.yaml
    ```

