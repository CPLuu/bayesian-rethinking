# Statistical Rethinking 2023 in Python
Python/PyMC 5 implementations of Richard McElreath's outstanding lecture series [Statistical Rethinking 2023](https://www.youtube.com/playlist?list=PLDcUM9US4XdPz-KxHM4XHt7uUVGWWVSus).


## Setup
The python environment for all notebooks depends on packages gathered for macOS with M1 Pro. Manage the environment using [miniconda](https://docs.conda.io/en/latest/miniconda.html). If you are on a similar hardware setup, you can initialize the conda environment and jupyter notebook via the standard workflow:

```bash
$ conda env create -f stat-rethink-pymc5.yml
$ conda activate stat-rethink-pymc5
$ jupyter lab 
```


Otherwise, the Python version and standard packages that are imported in the notebooks via the `init_notebook.py` script are as follows:

```
Watermark:
----------
Python implementation: CPython
Python version       : 3.10.12
IPython version      : 8.15.0

Compiler    : Clang 15.0.7 
OS          : Darwin
Release     : 22.2.0
Machine     : arm64
Processor   : arm
CPU cores   : 10
Architecture: 64bit

statsmodels: 0.14.0
numpy      : 1.24.4
arviz      : 0.16.1
scipy      : 1.11.2
pymc       : 5.8.0
pandas     : 2.1.0
xarray     : 2023.8.0
matplotlib : 3.7.2
```

## Authors
- Dustin Stansbury (Translated the lectures to PyMC5) - https://github.com/dustinstansbury/statistical-rethinking-2023
- Cuong Luu (Edited lecture notebooks for clarity, and added homework solution in python) - https://github.com/CPLuu/bayesian-rethinking/tree/main/lectures_2023
