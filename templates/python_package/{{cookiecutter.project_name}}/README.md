# {{ cookiecutter.project_name }}

<p align="center">

![CI Status](https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_name }}/actions/workflows/ci.yml/badge.svg)

  <!--
  <a href="https://coveralls.io/github/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}">
    <img src="https://coveralls.io/repos/github/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}/badge.svg?branch=main" alt="Test coverage percentage">
  </a>
  //-->
</p>

{{ cookiecutter.project_short_description }}

## Installation

Install this via pip (or your favourite package manager):

```bash
pip install {{ cookiecutter.project_slug }}
```

## Development

Install locally into virtualenv

```bash
virtualenv .venv
source .venv/bin/activate
pip install .[dev]
pip install .
pre-commit install
pre-commit install --hook-type commit-msg
```



## Documentation

[documentation](https://{{cookiecutter.project_slug}}.readthedocs.io)
