# Python project template

An opinionated [Copier](https://copier.readthedocs.io/en/stable/) template for Python projects managed by [PDM](https://pdm.fming.dev/latest/).

## Features

* [`src` directory layout](https://hynek.me/articles/testing-packaging/).
* [PDM](https://pdm.fming.dev/latest/) setup, with generated `pyproject.toml`.
* Pre-configured tools for code formatting, quality analysis, documentation and testing:
  * [ruff](https://github.com/charliermarsh/ruff)
  * [mypy](https://mypy.readthedocs.io/)
  * [pytest](https://docs.pytest.org/en/stable/)
  * [sphinx](https://sphinx-doc.org/) with [furo](https://pradyunsg.me/furo/) theme
  * [pip-audit](https://pypi.org/project/pip-audit/)
* Tests run with [Nox](https://nox.thea.codes/en/stable/).
* Support for [GitHub actions](https://github.com/features/actions) and [GitHub pages](https://pages.github.com/).

## Quickstart

To install Copier, please follow the installation instructions [here](https://copier.readthedocs.io/en/stable/#installation).

Then, to create a new project based on this template, run:

```shell
copier copy --trust 'https://github.com/vivienm/copier-python-pdm' path/to/your/project
```

and fill in the form.

To update an existing project based on this template, run:

```shell
copier update --skip-answered --trust
```

You will also need to install PDM, please follow the installation instructions [here](https://pdm.fming.dev/latest/#installation).
