# Brokest

More broke than a broker.

## Development

### Cloning

First, clone the project

```bash
git clone https://github.com/rentrueawng/brokest --recurse-submodules

# Go into the project root.
cd brokest
```

### Installation

First, install TA-Lib
```bash
# Get the TA-Lib library
git clone https://github.com/TA-Lib/ta-lib
cd ta-lib

# Install the library.
sudo ./install
```

You might need to enter your password.

Then, install the build tool poetry

```bash
pipx install poetry

# Or using pip
pip install poetry.
```

Then, install the packages from PyPI, in editable mode.
```bash
poetry install
```
