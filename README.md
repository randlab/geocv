# geocv: Examples of systematic cross-validation of categorical geostatistical simulations

This repository contains data and code illustrating the following work:
A framework for the cross-validation of categorical geostatistical simulations by Przemysław Juda, Philippe Renard, and Julien Straubhaar.

## Reproducing environment
The workflow is presented in jupyter notebooks.
Python 3.6.9 was used to complete the study.
The best is to start with an empty virtual environment
and install all packages.
In order to reproduce the environment, 
use pip to install the requirements: `pip install -r requirements.txt`.

This will install jupyter notebook and required dependencies to run notebooks.

## Data
The input data required to reproduce the results is in `data` directory.

## Reference
The reference outputs of jupyter notebooks are in the `reference` directory.

## Reproducing the workflow
The directories `samples`, `output` and `figures` are empty. They can be populated by running notebooks.

Run notebooks in the following order:
- 1-preprocessing.ipynb,
- 2-results.ipynb,
- 3-analysis.ipynb.

The generated output should be the same as that in the `reference` directory.
