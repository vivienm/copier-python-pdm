# Python project template

An opinionated [Copier](https://copier.readthedocs.io/en/stable/) template for Python projects managed by [PDM](https://pdm.fming.dev/latest/).

## Features

* [`src` directory layout](https://hynek.me/articles/testing-packaging/).
* [PDM](https://pdm.fming.dev/latest/) setup, with generated `pyproject.toml`.
* Pre-configured tools for code formatting, quality analysis and testing:
  * [black](https://github.com/psf/black)
  * [isort](https://pycqa.github.io/isort/)
  * [flake8](https://flake8.pycqa.org/en/latest/) with [pydocstyle](https://github.com/PyCQA/pydocstyle/) plugin
  * [mypy](https://mypy.readthedocs.io/)
  * [pytest](https://docs.pytest.org/en/stable/).
  * [pip-audit](https://pypi.org/project/pip-audit/)
* Tests run with [Nox](https://nox.thea.codes/en/stable/).
* Support for [GitHub actions](https://github.com/features/actions).

## Quickstart

Make sur all the [requirements](#requirements) are met, then:

```shell
copier 'https://github.com/vivienm/copier-python-pdm.git' path/to/your/project
```

Or even shorter:

```shell
copier 'gh:vivienm/copier-python-pdm' /path/to/your/new/project
```

## Requirements

To use this Copier template, you will need:

* [Git](https://git-scm.com/)
* [Python 3](https://www.python.org/)
* [Copier](https://copier.readthedocs.io/en/stable/)
* [PDM](https://pdm.fming.dev/latest/)

### Copier

To install copier, you may follow its [installation instructions](https://copier.readthedocs.io/en/stable/#installation) or use [pipx](https://pipxproject.github.io/pipx/):

```shell
pipx install copier
```

### PDM

To install PDM, you may follow its [installation instructions](https://pdm.fming.dev/latest/#installation), or use pipx:

```shell
pipx install pdm
```

You will also need to [enable PEP 582 globally](https://pdm.fming.dev/latest/#enable-pep-582-globally), e.g. on Bash:

```shell
pdm --pep582 >> ~/.bash_profile
```
