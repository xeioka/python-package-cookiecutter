# {{ cookiecutter.project_name }}

[![Linting]({{ cookiecutter.__repository_url }}/actions/workflows/linting.yaml/badge.svg)]({{ cookiecutter.__repository_url }}/actions/workflows/linting.yaml)

{{ cookiecutter.project_description }}

## Requirements

- [Python](https://www.python.org) >= {{ cookiecutter.python_version }};

## Installation

From GitHub repository (see [pip documentation](https://pip.pypa.io/en/stable/topics/vcs-support/#git) or run `pip install --help`):

```sh
pip install git+ssh://git@github.com/{{ cookiecutter.repository_user }}/{{ cookiecutter.repository_name }}.git
```

## Contributing

See [Contributing](/docs/contributing.md).
