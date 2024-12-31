<div align="center">

# Python Package Template

A base repo for a Python package using poetry for project management

[![PyPI - Version](https://img.shields.io/pypi/v/<package_name>?logo=pypi)](https://pypi.org/project/<package_name>/)
[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/<package_name>?logo=python)](https://pypi.org/project/<package_name>/)
[![GitHub License](https://img.shields.io/github/license/<github_user>/<github_repo_name>)](https://github.com/<github_user>/<github_repo_name>/blob/master/LICENSE)
[![PyPI - Downloads](https://img.shields.io/pypi/dm/<package_name>)](https://pypistats.org/packages/<package_name>)
[![linting - Ruff](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json)](https://github.com/<github_user>/<github_repo_name>/actions/workflows/ruff.yaml)
[![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit)](https://github.com/pre-commit/pre-commit)

</div>

## What's included?

- Package management with `poetry`
- Linting and formatting with `ruff`
- Testing and coverage with `pytest` and `coverage` (`pytest-cov`)
- GitHub Actions for `ruff` checks on PRs and pushes
- VS Code settings and recommended extensions
- Keep a changelog template
- GitHub issue forms templates for bugs and feature requests
- Generic `CONTRIBUTING.md`
- Pre-commit hooks

## Who can use this template?

You can use this template if:

- Your project requires python 3.11 or higher
- VS code is your default text editor

## How to prepare the template after forking it?

Search the entire tree and replace this 4 strings

- `<author>`: Your name
- `<github_repo_name>`: Your GitHub repo name
- `<github_user_name>`: Your GitHub username
- `<package_name>`: The name you what to use for the package


## TODO

- [ ] Add GitHub Action for PyPi Release
- [ ] Add `tox` for environment testing
- [ ] Add GitHub Action for running `tox` with matrix
