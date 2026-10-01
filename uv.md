# uv - Python Package and Project Manager

## Install uv - one-liner

```sh
winget install astral-sh.uv # on Windows
dnf install uv # on Fedora Linux
brew install uv # on MacOS or Linux with Homebrew
```

## Run a Python script

`uv` reads `pyproject.toml` from the local directory to automatically create a Python virtual environment with the correct version of Python with all project dependencies and then runs the script as expected. Use the following command-

```sh
uv run script.py # automatically detects or installs Python
```
