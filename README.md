# Helpful GitHub Workflows

## Usage
The easiest way to "copy" a workflow into your own package is as follows:
  - Add sodre/workflows as a remote and fetch all branches
    ```bash
    git remote add ghw-sodre https://github.com/sodre/workflows.git
    git fetch ghw-sodre
    ```
  - Copy the workflow that you want to use
    ```
    git --work-tree=.github/workflows/ checkout remotes/ghw-sodre/master -- pypa-conda.yml
    ```

