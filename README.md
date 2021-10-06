# geocv: Examples of systematic cross-validation of categorical geostatistical simulations

This accompanies the following work:  
Juda, P., Renard, P., & Straubhaar, J. (2020). A framework for the cross-validation of categorical geostatistical simulations. Earth and Space Science, 7, e2020EA001152. https://doi.org/10.1029/2020EA001152  
The version of the data and the software cited by the paper: [![DOI](https://zenodo.org/badge/240537037.svg)](https://zenodo.org/badge/latestdoi/240537037)

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
