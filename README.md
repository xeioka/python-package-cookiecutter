# Python Package Cookiecutter

Get the oven ready!

## Requirements

1. [Cookiecutter](https://www.cookiecutter.io) >= 2.6.0;

## Usage

1. Cut your cookie (see [cookiecutter documentation](https://cookiecutter.readthedocs.io/en/stable/usage.html) or run `cookiecutter --help`):

    ```sh
    cookiecutter git@github.com:xeioka/python-package-cookiecutter.git
    ```

2. Create a GitHub repository (requires [GitHub CLI](https://cli.github.com)):

    ```sh
    cd {project-name}
    git init && git add . && git commit -m "Add Python package."
    gh repo create
    ```

## Contributing

See [Contributing](/docs/contributing.md).
