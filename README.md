# cookiecutter-uv

This is a fork of [fpgmaas/cookiecutter-uv](https://github.com/fpgmaas/cookiecutter-uv.git), a minimalist Cookiecutter template that can be used to initiate a Python project with the minimum necessary tools for development, testing, and deployment. It supports the following features:

- [uv](https://docs.astral.sh/uv/) for dependency management
- Supports both [src and flat layout](https://packaging.python.org/en/latest/discussions/src-layout-vs-flat-layout/).
- CI/CD with [GitHub Actions](https://github.com/features/actions)
- Pre-commit hooks with [pre-commit](https://pre-commit.com/)
- Code quality with [ruff](https://github.com/charliermarsh/ruff), [pyright](https://microsoft.github.io/pyright/), [deptry](https://github.com/fpgmaas/deptry/) and [black](https://black.readthedocs.io/)
- Publishing to [PyPI](https://pypi.org) by creating a new release on GitHub
- Testing and coverage with [pytest](https://docs.pytest.org/en/7.1.x/) and [codecov](https://about.codecov.io/)
- Documentation with [MkDocs](https://www.mkdocs.org/)
- Compatibility testing for multiple versions of Python with [tox-uv](https://github.com/tox-dev/tox-uv)
- Containerization with [Docker](https://www.docker.com/)
- Development environment with [VSCode devcontainers](https://code.visualstudio.com/docs/devcontainers/containers)

## Quickstart

Before starting, ensure you have [uv](https://docs.astral.sh/uv/) installed. If not, follow the installation instructions in the [uv installation documentation](https://docs.astral.sh/uv/getting-started/installation/).

Then on your local machine, navigate to the directory in which you want to create a project directory, and run the following command:

```bash
uvx cookiecutter https://github.com/VanderpoelLiam/cookiecutter-uv.git
```

Follow the prompts to configure your project. Once completed, a new directory containing your project will be created. Then navigate into your newly created project directory and follow the instructions in the `README.md` to complete the setup of your project.

## Syncing with Upstream

To sync this fork with the upstream repository:

```bash
git remote add upstream https://github.com/fpgmaas/cookiecutter-uv.git
git fetch upstream
git merge upstream/main
git push origin main
```

## Acknowledgements

This project is a fork of [fpgmaas/cookiecutter-uv](https://github.com/fpgmaas/cookiecutter-uv.git).
