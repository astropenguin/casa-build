# casa6-test
:house: Python environment for testing modular CASA 6 installation

## Requirements

- pipenv
- pyenv

You can install them by [Homebrew](https://brew.sh):

```bash
$ brew install pyenv pipenv
```

## Installation

```shell
$ git clone --recursive https://github.com/astropenguin/casa6-test.git
$ cd casa6-test
$ pipenv install
$ etc/configure
```

### What etc/configure does?

- creates IPython, Jupyter, matplotlib custom configs.
- add backend setting of matplotlib (see hooks/hook-post)

For more information, please see [astropenguin/pipenv-analysis-configs](https://github.com/astropenguin/pipenv-analysis-configs).

## Usage

Run (I)Python:

```shell
$ pipenv run ipython
```

Then import `casatasks`:

```python
In [1]: import casatasks
```
