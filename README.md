[![Run unit tests](https://github.com/jarw2/software-engineering-ci/actions/workflows/unit-tests.yml/badge.svg)](https://github.com/jarw2/software-engineering-ci/actions/workflows/unit-tests.yml)

[![Run os tests](https://github.com/jarw2/software-engineering-ci/actions/workflows/os-tests.yml/badge.svg)](https://github.com/jarw2/software-engineering-ci/actions/workflows/os-tests.yml)

[![BCH compliance](https://bettercodehub.com/edge/badge/jarw2/software-engineering-ci?branch=main)](https://bettercodehub.com/)

# OxRSE Continuous Integration course

This project contains a small Python project. We are going to use free cloud services to automate:

- unit testing on multiple Python versions
- unit testing on multiple operating systems
- coverage testing
- static analysis
- documentation generation

To make sure all dependencies are installed, we recommend creating a new virtual environment.
From the directory containing this file:

```bash
python3 -m pip install --user virtualenv
python3 -m venv venv
```

Activate the virtual environment:

Linux / macOS:
```bash
source venv/bin/activate
```

Windows cmd.exe:
```bash
venv\Scripts\activate.bat
```

Windows PowerShell:
```bash
venv\Scripts\Activate.ps1
```

Windows using Git Bash:
```bash
source venv\Scripts\activate
```

Upgrade the build tools and install this project:

```bash
pip install --upgrade pip setuptools wheel
pip install -e .[dev,docs]
```
