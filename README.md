[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.570048.svg)](https://doi.org/10.5281/zenodo.570048)

# OHSU Library OpenRefine

**Cleaning Data Cleaning with OpenRefine** Lesson adapted from [Data Carpentry](https://datacarpentry.org/lessons/#ecology-workshop) by the OHSU Library

## OpenRefine Version

The current version has been tested with OpenRefine 3.7.2 on May 2023.

## Data set notes

- This data set is derived from [The Portal Project Long-term desert ecology](https://portal.weecology.org/) project data. [This data file](https://www.esapubs.org/archive/ecol/E090/118/Portal_rodents_19772002.csv) was downloaded and then modified specifically for use with OpenRefine.
  - Taxon names were put back into the file.
  - The number of rows was reduced to simplify the reconciliation and URL parsing exercises.
  - These modifications were made in order to illustrate some features of Open Refine.
    - Errors were added to the taxon names (`scientificName` field), to demonstrate OpenRefine's ability to find likely mis-entered data.
    - These errors can be found using clustering algorithms on the `scientificName` column, showing the power of the algorithms to find discrepancies quickly and making it simple to fix all issues found.

