# {{ cookiecutter.project_name }}

[![Linting]({{ cookiecutter.__repository_url }}/actions/workflows/linting.yaml/badge.svg)]({{ cookiecutter.__repository_url }}/actions/workflows/linting.yaml)
{% if cookiecutter.project_description %}

{{ cookiecutter.project_description }}
{% endif %}

## Requirements

1. [Python](https://www.python.org) >= {{ cookiecutter.python_version }};

## Usage

Install from GitHub repository (see [the documentation](https://pip.pypa.io/en/stable/topics/vcs-support/#vcs-support) or run `pip install --help`):

```sh
pip install git+ssh://git@github.com/{{ cookiecutter.repository_user }}/{{ cookiecutter.repository_name }}.git
```

## Contributing

1. Clone the repository:

    ```sh
    git clone git@github.com:{{ cookiecutter.repository_user }}/{{ cookiecutter.repository_name }}.git
    cd {{ cookiecutter.repository_name }}
    ```

2. Create a Python virtual environment and install the requirements:

    ```sh
    python{{ cookiecutter.python_version }} -m venv .venv && source .venv/bin/activate
    pip install -r requirements/dev.txt
    ```

3. Install pre-commit hooks:

    ```sh
    pre-commit install
    ```
