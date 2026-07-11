# Termux Twine & Build
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Python Version](https://img.shields.io/badge/python-3.6%2B-blue.svg)](https://www.python.org)
[![PyPI version](https://img.shields.io/pypi/v/termux-twine-build.svg?color=blue)](https://pypi.org/project/termux-twine-build/)
[![PyPI downloads](https://img.shields.io/pypi/dm/termux-twine-build.svg)](https://pypi.org/project/termux-twine-build/)


## This package installs multiple pip packages that allow twine and build to work on Termux
### Aware: Certain commands like twine check may not work **however** commands like twine upload dist/* or python -m build should have full functionality

## Installation
### Install the package, it should install every package needed for twine and build to work on termux
```python
pip install termux-twine-build
```

### Uninstall the unneeded pip package
```python
pip uninstall termux-twine-build
```
### Use twine or build like normal
#### Ex: building the dist files
```bash
python -m build
```
#### Ex: uploading to pypi
```bash
twine upload dist/*
```
## Links!
### Create an issue [Here](https://github.com/Ruizennis/Termux-Twine-Build/issues)!

### View the pypi package [Here](https://pypi.org/project/termux-twine-build/)!
___
# Project is licensed under the Mit license, see [LICENSE](LICENSE).