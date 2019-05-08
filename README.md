# casa6-test
:house: Python environment for testing modular CASA 6 installation

## Installation

```shell
$ git clone --recursive https://github.com/astropenguin/casa6-test.git
$ cd casa6-test
$ pipenv install --skip-lock
$ etc/configure
```

Note that pipenv takes very long time to create Pipfile.lock.
I recommend not to create it by specifying `--skip-lock`.

### What etc/configure does?

- creates IPython, Jupyter, matplotlib custom configs.
- fixes wrong dylib links (see hooks/hook-post)
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
