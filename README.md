# Solar Flare Prediction – RHESSI Mission

## Data Preprocessing

The preprocessing of the dataset involved the following steps:

1. **Data Source**: The dataset was sourced from the NASA RHESSI Data Repository, accessible via a web form on [this page](https://hesperia.gsfc.nasa.gov/rhessi_data_search/rhessi_data_search_vme.html).
2. **FITS to CSV Conversion**: The original data files were in FITS format, which were converted to CSV format using the tools available [here](https://fits.gsfc.nasa.gov/fits_viewer.html).
3. **Dataset Compilation**: Multiple CSV files generated from the FITS files were concatenated to create the current dataset. The script used to perform this concatenation can be found in this [repository](https://github.com/Byte7/Solar-Flares-RHESSI-Mission/tree/master/Join_script).

The complete dataset is available in the repository [here](https://github.com/Byte7/Solar-Flares-RHESSI-Mission/tree/master/data).

## Model Performance

The following machine learning models were used to predict the energy range of solar flares based on various flare attributes. The top three models, ranked by accuracy, are:

1. **Gradient Boosting Classifier** – Achieved an accuracy of 87%
2. **Random Forest Classifier** – Achieved an accuracy of 86%
3. **Decision Tree Classifier** – Achieved an accuracy of 82%
