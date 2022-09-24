# Dissertation notebooks

This repository holds some notebooks that generate some of the figures in Dominique Sydow's disseration (and are referenced in the dissertation accordingly).

## Installation

1. Clone this repository and move to the downloaded folder
    ```
    git clone git@github.com:dominiquesydow/dissertation_notebooks.git
    cd /path/to/dissertation_notebooks
    ```
2. Install and activate environment
    ```
    mamba env create -f environment.yaml
    # Or MacOS with M1 chip
    CONDA_SUBDIR=osx-64 mamba env create -f environment.yaml

    conda activate dissertation
    ```
3. Fire up Jupyter Lab to run notebooks
    ```
    jupyter lab
    ```