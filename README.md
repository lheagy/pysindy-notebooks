# pysindy-notebooks

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lheagy/pysidny-notebooks/master)

Example notebooks that explore using [PySINDy](https://pysindy.readthedocs.io/en/latest/index.html) for the Sparse Identification of Nonlinear Dynamical systems. The review reference we are following is [de Silva et al (2020)](https://arxiv.org/pdf/2004.08424.pdf)

## Usage

To run the notebooks locally, you will need to have python installed,
preferably through [anaconda](https://www.anaconda.com/download/) .

You can then clone this repository. From a command line, run

```
git clone https://github.com/lheagy/pysindy-notebooks.git
```

Then `cd` into the `pysindy-notebooks` directory:

```
cd pysindy-notebooks
```

To setup your software environment, we recommend you use the provided conda environment

```
conda env create -f environment.yml
conda activate pysindy
```

You can then launch Jupyter

```
jupyter notebook
```

Jupyter will then launch in your web-browser.

