# Mobgap Validation Results

This repository contains the validation results for the algorithm implemented in [mobgap]().
The scripts that generated these results are located in the `revalidation` directory of the [mobgap repository]().
All results are calculated using the TVS dataset, which is available via Zenodo at [this link](https://zenodo.org/records/13987963).

## Version Information

- For each release of the `mobgap` package, we also tag/release a corresponding version of this repository (even if no changes were made to the validation results).
- Until version 0.11.0, all validation results were generated using the version `1 .0.1` of the TVS dataset.


## Working with the Results

While you can just download the individual files, we recommend using the `mobgap` package to load the results.
We provide a `ValidationResultLoader` class that can be used to load the results from this repository.
It will automatically download the requested files.