![alt text](https://github.com/atomgptlab/alignn/actions/workflows/main.yml/badge.svg)
[![codecov](https://codecov.io/gh/atomgptlab/alignn/branch/main/graph/badge.svg?token=S5X4OYC80V)](https://codecov.io/gh/atomgptlab/alignn)
[![PyPI version](https://badge.fury.io/py/alignn.svg)](https://badge.fury.io/py/alignn)
![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/atomgptlab/alignn)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/atomgptlab/alignn)
![GitHub commit activity](https://img.shields.io/github/commit-activity/y/atomgptlab/alignn)
[![Downloads](https://pepy.tech/badge/alignn)](https://pepy.tech/project/alignn)

> 📖 **Full documentation:** https://atomgptlab.github.io/alignn/

# Table of Contents
* [Introduction](#intro)
* [Installation](#install)
* [Examples](#example)
* [Pre-trained models](#pretrained)
* [JARVIS-ALIGNN webapp](#webapp)
* [ALIGNN-FF & ASE Calculator](#alignnff)
* [Peformances on a few datasets](#performances)
* [Useful notes](#notes)
* [References](#refs)
* [How to contribute](#contrib)
* [Correspondence](#corres)
* [Funding support](#fund)

<a name="intro"></a>
# ALIGNN & ALIGNN-FF (Introduction)

The Atomistic Line Graph Neural Network ([paper](https://www.nature.com/articles/s41524-021-00650-1)) introduces a graph convolution layer that explicitly models both two- and three-body interactions in atomistic systems. The ALIGNN-FF variant ([paper](https://pubs.rsc.org/en/content/articlehtml/2023/dd/d2dd00096b)) extends this to a force-field for structurally and chemically diverse systems across 89 elements.

See [docs/index.md](docs/index.md) for the full introduction.

![ALIGNN layer schematic](https://github.com/atomgptlab/alignn/blob/develop/alignn/tex/schematic_lg.jpg)

<a name="install"></a>
## Installation

See [docs/installation.md](docs/installation.md) for conda, GitHub, and pip installation methods.

<a name="example"></a>
## Examples

See [docs/training/](docs/training/) for dataset format and training examples:

- [Dataset format](docs/training/dataset-format.md)
- [Single-output regression](docs/training/single-output-regression.md)
- [Classification](docs/training/classification.md)
- [Multi-output regression](docs/training/multi-output-regression.md)
- [Force-field training](docs/training/force-field.md)
- [Multi-GPU training](docs/training/multi-gpu.md)

Google Colab notebooks are linked from [docs/index.md](docs/index.md).

<a name="pretrained"></a>
## Using pre-trained models

See [docs/pretrained/](docs/pretrained/):

- [Property predictor](docs/pretrained/property-predictor.md)
- [ALIGNN-FF](docs/pretrained/alignn-ff.md)

<a name="webapp"></a>
## Web-apps

See [docs/usage/webapps.md](docs/usage/webapps.md). Direct links: [AtomGPT ALIGNN app](https://atomgpt.org/alignn), [ALIGNN-FF app](https://atomgpt.org/alignn_ff_dynamics).

<a name="alignnff"></a>
## ALIGNN-FF ASE Calculator

See [docs/usage/ase-calculator.md](docs/usage/ase-calculator.md) for example usage.

<a name="performances"></a>
## Performances

See [docs/performance.md](docs/performance.md) for benchmark tables on JARVIS-DFT, Materials Project, QM9, hMOF, qMOF, OpenCatalyst, and other datasets. Also see [JARVIS-Leaderboard](https://pages.nist.gov/jarvis_leaderboard/).

<a name="notes"></a>
## Useful notes

See [docs/notes.md](docs/notes.md) for common pitfalls and FAQs.

<a name="refs"></a>
## References

See [docs/references.md](docs/references.md) for the publication list.

<a name="contrib"></a>
## How to contribute

See [Contribution instructions](https://github.com/atomgptlab/jarvis/blob/master/Contribution.rst) and [docs/contributing.md](docs/contributing.md).

<a name="corres"></a>
## Correspondence

Please report bugs as [GitHub issues](https://github.com/atomgptlab/alignn/issues) or email drkamal@jhu.edu.

<a name="fund"></a>
## Funding support

- [NIST-MGI](https://www.nist.gov/mgi)
- [NIST-CHIPS](https://www.nist.gov/chips)

## Code of conduct

Please see [Code of conduct](https://github.com/atomgptlab/jarvis/blob/master/CODE_OF_CONDUCT.md).
