# Python Package Cookiecutter

Cookiecutter for a Python package.

## Requirements

- [Cookiecutter](https://www.cookiecutter.io) >= 2.6.0;

## Usage

1. Generate project skeleton (see [Cookiecutter documentation](https://cookiecutter.readthedocs.io/en/stable/usage.html) or run `cookiecutter --help`):

    ```sh
    cookiecutter git@github.com:xeioka/python-package-cookiecutter.git
    ```

2. Create GitHub repository (requires [GitHub CLI](https://cli.github.com)):

    ```sh
    cd {project-name}
    git init && git add . && git commit -m "Add project skeleton."
    gh repo create
    ```
