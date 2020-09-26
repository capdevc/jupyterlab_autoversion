# jupyterlab_autoversion
Automatically version jupyter notebooks in JupyterLab

[![Build Status](https://dev.azure.com/tpaine154/jupyter/_apis/build/status/timkpaine.jupyterlab_autoversion?branchName=master)](https://dev.azure.com/tpaine154/jupyter/_build/latest?definitionId=16&branchName=master)
[![Coverage](https://img.shields.io/azure-devops/coverage/tpaine154/jupyter/16/master)](https://dev.azure.com/tpaine154/jupyter/_build?definitionId=16&_a=summary)
[![GitHub issues](https://img.shields.io/github/issues/timkpaine/jupyterlab_autoversion.svg)]()
[![PyPI](https://img.shields.io/pypi/l/jupyterlab_autoversion.svg)](https://pypi.python.org/pypi/jupyterlab_autoversion)
[![PyPI](https://img.shields.io/pypi/v/jupyterlab_autoversion.svg)](https://pypi.python.org/pypi/jupyterlab_autoversion)
[![npm](https://img.shields.io/npm/v/jupyterlab_autoversion.svg)](https://www.npmjs.com/package/jupyterlab_autoversion)


## Save every notebook revision
Enhanced checkpoints, versioned and persistent between restarts on every save

![](https://raw.githubusercontent.com/timkpaine/jupyterlab_autoversion/master/docs/example.gif)


## Install

```bash
pip install jupyterlab_autoversion
jupyter lab build
```

# Devlopment

## Dev install

```bash
# at the root of jupyterlab_autoversion repo
make dev_install
```

## Debug Python and Typescript code using vscode

vscode is able to debug both the Python and Typescript sections of this project, and can do so in a single run. However, vscode will first require a specific launch config before you can debug with it. You can create this launch config by first running

```bash
make debug_init
```

and then editing the resulting `.vscode/launch.json` and `.vscode/jupyterlab_venv.env` files as needed
