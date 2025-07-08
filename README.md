# Next-day gridded forecast database for California (code and tutorial)

Repository containing the code and tutorial to evaluate against observed data, and compare against each other, models from the next-day CSEP forecast database for California. The files contained here are supplementary material for the article *A benchmark database of ten years of prospective next-day earthquake forecasts in California from the Collaboratory for the Study of Earthquake Predictability* on Nature Scientific Data.

The tutorial provides guidance on how to install pyCSEP; how to download the models in the Next-day CSEP forecasts database for California; how to load and visualise forecasts; how to create cumulative forecasts for custom time periods; how to perform CSEP consistency and comparison tests. The code contains all the function illustrated in the tutorial. Both heavily relies on the use of the [pyCSEP toolkit](https://github.com/SCECcode/pycsep) to visualise forecasts, evaluate them against observed data, and compare forecasts from different models.

The tutorial uses the forecasts produced by the ETAS and STEP models as examples. The HDF5 files corresponding to the forecasts need to be downloaded separately. They can be downloaded from [Zenodo](https://zenodo.org/records/15076187) along with the other models in the database, or separately from the [CSEP website](https://cseptesting.org/grid-based-forecasts/). 

## Files

The `Example_model` folder contains an example forecast used to show how to convert forecasts in CSV file format, organised in a system of nested folder, in HDF5 file format.

The files `functions_for_hdf5.py` and `functions_for_hdf5_parallel.py` contain the functions used in the tutorial to evaluate the forecasts. The second one is just the parallel version of the first one.

The `tutorial.ipynb` is the tutorial as a Jupyter notebook, while `tutorial.pdf` is the corresponding pdf file.

## How to cite

To cite this code in publications please use:

Serafini, F., Bayona, J.A., Silva, F., Savran, W., Stockman, S., Maechling, P.J., Werner, M.J. (under review) A benchmark database of ten years of prospective next-day earthquake forecasts in California from the Collaboratory for the Study of Earthquake Predictability, *Sci Data*. 

