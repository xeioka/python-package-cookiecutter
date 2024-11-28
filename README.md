# Python Package Cookiecutter

> _Namespaces are one honking great idea -- let's do more of those!_

Get the oven ready!

## Requirements

1. [Cookiecutter](https://www.cookiecutter.io) >= 2.6.0 (usage);

## Usage

1. Cut your cookie (see [pip documentation](https://cookiecutter.readthedocs.io/en/stable/usage.html) or run `cookiecutter --help`):

    ```sh
    cookiecutter git@github.com:xeioka/python-package-cookiecutter.git
    ```

2. Create a GitHub repository (requires [GitHub CLI](https://cli.github.com)):

    ```sh
    cd {project-name}
    git init && git add . && git commit -m "Add Python package."
    gh repo create
    ```
