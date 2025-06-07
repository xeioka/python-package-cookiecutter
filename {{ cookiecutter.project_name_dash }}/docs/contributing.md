# Contributing

## Requirements

- [Python](https://www.python.org) >= {{ cookiecutter.python_version }};

## Setup

1. Clone the repository:

    ```sh
    git clone git@github.com:{{ cookiecutter.repository_user }}/{{ cookiecutter.repository_name }}.git
    cd {{ cookiecutter.repository_name }}
    ```

2. Create Python virtual environment and install the requirements:

    ```sh
    python{{ cookiecutter.python_version }} -m venv .venv
    source .venv/bin/activate
    pip install --upgrade pip
    pip install -r requirements/dev.txt
    ```

3. Install pre-commit hooks:

    ```sh
    pre-commit install
    ```
