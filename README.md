# env-setup-playground
Explore different environment setup configs

## Setup
* Install `make`
* Install `poetry` [[doc](https://python-poetry.org/docs/basic-usage/)]
  * Run `poetry new env-setup-playground` to create a new project
  * The new project should have the following structure:
    ```
    env-setup-playground
    ├── pyproject.toml
    ├── README.rst
    ├── src
    │   └── env_setup_playground
    │       └── __init__.py
    └── tests
        ├── __init__.py
        └── test_env_setup_playground.py
    ```
* Install `podman`
* Under the project repo, run `touch Makefile` to create the Makefile
* Run `poetry completions fish > ~/.config/fish/completions/poetry.fish` to enable poetry auto completions in fish shell

## Appendix
* [Makefile tutorial](https://makefiletutorial.com/)
