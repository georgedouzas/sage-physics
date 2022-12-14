# Sage Physics

[![ci](https://github.com/georgedouzas/sage-physics/workflows/ci/badge.svg)](https://github.com/georgedouzas/sage-physics/actions?query=workflow%3Aci)
[![documentation](https://img.shields.io/badge/docs-mkdocs%20material-blue.svg?style=flat)](https://georgedouzas.github.io/sage-physics/)
[![pypi version](https://img.shields.io/pypi/v/sage-physics.svg)](https://pypi.org/project/sage-physics/)
[![gitpod](https://img.shields.io/badge/gitpod-workspace-blue.svg?style=flat)](https://gitpod.io/#https://github.com/georgedouzas/sage-physics)
[![gitter](https://badges.gitter.im/join%20chat.svg)](https://gitter.im/sage-physics/community)

A Python package to create and simulate physics models. It is based on the open-source Computer Algebra System [SageMath](https://www.sagemath.org/).

## Installation

There two main ways of installing the library. The first is for users while the second is need for
development and it uses [PDM](https://pdm.fming.dev/latest/) as the package manager.

### User

With `pip`:

```bash
sage --pip install sage-physics
```

### Developement

```bash
git clone https://github.com/georgedouzas/sage-physics.git
cd sage-physics
SAGE_PATH=$(sage --root)/venv/bin
pdm use $SAGE_PATH/python3
pdm --pep582 >> $SAGE_PATH/sage-env-config
pdm install
```
