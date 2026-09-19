# CS6956 MDN Experiments

This repository contains the notebook experiments for the Probabilistic Deep Learning assignment.

## Setup with Miniconda or Anaconda

The recommended setup uses the Conda environment described in [environment.yml](environment.yml). From the repository directory (`CS6956-MDN`), open Anaconda Prompt or a new VS Code PowerShell terminal and run:

```text
conda env create -f environment.yml
conda activate cs6956-mdn
python -m ipykernel install --user --name cs6956-mdn --display-name "Python (CS6956-MDN)"
```

If the environment already exists and the YAML file has changed, update it with:

```text
conda env update -f environment.yml --prune
```

In VS Code, open `mdn_2d_starter.ipynb`, select the `Python (CS6956-MDN)` kernel, and run the notebook cells from top to bottom.

To leave the Conda environment:

```text
conda deactivate
```

To remove the environment completely:

```text
conda env remove --name cs6956-mdn
```

## Optional pip setup

If Conda is unavailable, [requirements.txt](requirements.txt) can be used with a standard Python virtual environment. The Conda workflow above is the primary, reproducible setup for this project.
