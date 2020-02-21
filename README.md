# Cross-validation of geostatistical simulations

## Installation
Requires python3.6 or newer. Use pip to install `pip install -r requirements.txt`.
This will install jupyter notebook and required dependencies to run notebooks.
A geone package is required but it is not yet available publicly. It will be released soon.

## Data
The input data required to reproduce the results is in `data` directory.

## Reference
The reference outputs of jupyter notebooks are in the `reference` directory.

## Reproducing the workflow
The directories `samples`, `output` and `figures` are empty. They can be populated by running notebooks.

Run notebooks in the following order:
- preprocessing,
- results,
- analysis.

The generated output should be the same as that in the `reference`.

The notebook `split-k-fold.ipynb` is only for producing a figure for publication.

