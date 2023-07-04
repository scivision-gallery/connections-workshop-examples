# Example notebooks for the [scivision](https://github.com/alan-turing-institute/scivision) project

This repo contains the following example notebooks, which can be run with Jupyter notebook:
1. Butterfly classification
2. Flower classification

Both of these demo the use of the `scivision` package and catalog.
  
To run the notebooks in this repo locally, do the following:

1. Open your terminal
2. Check your conda installation with `conda --version`. If you don't have conda, install it by following [these instructions](https://docs.conda.io/en/latest/miniconda.html)
3. Clone the repository into your current folder `git clone https://github.com/scivision-gallery/connections-workshop-examples` 
4. Change directory to the cloned repository, `cd connections-workshop-examples` 
5. Create an environment for the notebooks: `conda env create -f environment.yml`
6. Activate it: `conda activate connections-workshop`
7. Open the notebooks in this repo with `jupyter notebook`

A full conda environment can be found in environment_full.yml. If you are having issues creating the conda environment, this file contains details of all the packages and their versions which are required to run these notebooks, including secondary and tertiary dependencies.

**Visit the [Scivision Gallery](https://github.com/scivision-gallery) to see more examples and use-cases.**
