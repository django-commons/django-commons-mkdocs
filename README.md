# Django Commons mkdocs

The Django Commons docs are deployed at [django-commons.org](https://django-commons.org).

The repository that hosts the docs is at https://github.com/django-commons/django-commons.github.io

## Local Development

1. Create a Python 3.13 virtual environment (`uv venv --python 3.13`)
2. Run `pip install mkdocs`
3. Run `mkdocs serve`

With uv: `uv run --python 3.13 --with mkdocs mkdocs serve`

### pre-commit

You don't have to use pre-commit. But if you choose to:

1. [Install pre-commit](https://pre-commit.com/#installation)
- Run `pre-commit install`

This will install pre-commit. Then, before you commit, run `pre-commit run` to run pre-commit and check your changed files for linting errors.

## MkDocs Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.
