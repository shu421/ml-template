# ml-template
## About
- This is a template repository for machine learning projects.
- Created with [uv](https://github.com/astral-sh/uv)

## Build Environment
1. Install [uv](https://docs.astral.sh/uv/#getting-started)
    ```bash
    curl -LsSf https://astral.sh/uv/install.sh | sh
    ```
2. Restart shell
    ```bash
    exec $SHELL -l
    ```

3. Add as a [repository template](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-template-repository) when creating a new GitHub repository.

### Usage
1. Install package dependencies.
    ```bash
    uv add numpy
    ```

2. Synchronize dependencies (this command should be run after adding new dependencies or creating a new environment).
    ```bash
    uv sync
    ```


## References
- [research-template](https://github.com/tubo213/research-template)
- [uvだけでPythonプロジェクトを管理する
](https://zenn.dev/turing_motors/articles/594fbef42a36ee)
