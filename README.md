# casa6-test
:house: Python environment for testing modular CASA 6 installation

# Installation

```shell
$ git clone --recursive https://github.com/astropenguin/casa6-test.git
$ cd casa6-test
$ pipenv install --skip-lock
$ etc/configure
```

# Usage

Run (I)Python:

```shell
$ pipenv run ipython
```

Then import `casatasks`:

```python
In [1]: import casatasks
```
