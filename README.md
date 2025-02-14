# uv_cookie
> Cookiecutter template for uv projects

This is a modern Cookiecutter template that can be used to create a Python project with all the necessary tools for development, testing, and linting. It supports the following features:

- [uv](https://docs.astral.sh/uv/) for dependency management
- [ruff](https://github.com/astral-sh/ruff) for linting
- [pytest](https://docs.pytest.org/en/latest/) for testing
- [pre-commit](https://pre-commit.com/) for pre-commit hooks
- CI/CD with [GitHub Actions](https://docs.github.com/en/actions)
- Comes with ([pandas](https://pandas.pydata.org/) and [numpy](https://numpy.org/)) pre-installed

## Quickstart

On your local machine, navigate to the directory in which you want to create a project directory, and run the following command:

```bash
uvx cookiecutter https://github.com/lobennett/uv_cookie.git
```

or if you don't have `uv` installed yet:

```bash
pip install cookiecutter
cookiecutter https://github.com/lobennett/uv_cookie.git
```

Follow the prompts to configure your project. Once completed, a new directory with the name `[project_slug]` will be created. Then navigate into your newly created project directory (e.g. `cd [project_slug]`) and follow the instructions in the `README.md` to complete the setup.

## Notes 

This project is based on [Jeanette](https://github.com/jmumford)'s packaging notes [repository](https://github.com/jmumford/packaging-notes).
