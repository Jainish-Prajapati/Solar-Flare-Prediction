# Solar Flare Prediction – RHESSI Mission

## Overview

This project focuses on predicting solar flare energy ranges using machine learning techniques, developed for the NASA Space Apps Challenge 2024 by **Team Arjuna**. Solar flares can have significant impacts on Earth's space environment, and accurate predictions are crucial for mitigating their effects. 

For more information about our team, visit our page [here](https://www.spaceappschallenge.org/nasa-space-apps-2024/find-a-team/arjuna/?tab=members).

## Data Preprocessing

The dataset used in this project was obtained from the **NASA RHESSI Data Repository** and underwent several preprocessing steps to prepare it for analysis and modeling. The key steps include:

1. **Data Source**: The dataset was sourced from the NASA RHESSI Data Repository, accessible via a web form on [this page](https://hesperia.gsfc.nasa.gov/rhessi_data_search/rhessi_data_search_vme.html).

2. **FITS to CSV Conversion**: The original data files were in **FITS** format, which were converted to **CSV** format using tools available [here](https://fits.gsfc.nasa.gov/fits_viewer.html).

3. **Dataset Compilation**: Multiple CSV files generated from the FITS files were concatenated to create the current dataset. The script used to perform this concatenation can be found in this [repository](https://github.com/Jainish-Prajapati/Solar-Flare-Prediction/tree/main/Join_script).

The complete dataset is available in the repository [here](https://github.com/Jainish-Prajapati/Solar-Flare-Prediction/tree/main/data).

## Project Breakdown

### Analysis

The data analysis phase involved:
- Understanding the characteristics of solar flares, including their **energy distribution**, **duration**, and **occurrence over time**.
- Identifying patterns in the dataset to guide the feature selection for predictive modeling.

### Prediction

Various machine learning models were built and trained to predict the energy range of a solar flare based on its attributes. The models include:
- **Linear Regression**
- **Logistic Regression**
- **Decision Tree**
- **Random Forest**
- **K-Nearest Neighbors (KNN)**
- **Gradient Boosting**
- **Neural Network**

### Model Performance

The top three machine learning models, ranked by accuracy, are as follows:

1. **Gradient Boosting Classifier** – Achieved an accuracy of **87%**
2. **Random Forest Classifier** – Achieved an accuracy of **86%**
3. **Decision Tree Classifier** – Achieved an accuracy of **82%**

### Evaluation

The models were evaluated using several performance metrics:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-score**

These metrics helped determine the effectiveness of each model in predicting the energy range of solar flares.

### Findings

- The **Random Forest** and **Gradient Boosting** models achieved the highest accuracy in predicting the energy range of solar flares.
- The project's findings contribute to the field of space weather research by providing a potential tool for predicting solar flares, which is critical for understanding and mitigating their impact on Earth.

## Conclusion

This project showcases the application of machine learning to space weather research, with a focus on predicting solar flares. The success of the **Gradient Boosting** and **Random Forest** models highlights their potential as robust tools in the field. Through this project, our team, **Arjuna**, aims to contribute to the advancement of solar flare prediction capabilities.

## Acknowledgments

- This project was developed as part of the **NASA Space Apps Challenge 2024** by **Team Arjuna**.
- Special thanks to the **NASA RHESSI Data Repository** for providing the data used in this analysis.

## Team Information

To learn more about **Team Arjuna** and its members, please visit our team page [here](https://www.spaceappschallenge.org/nasa-space-apps-2024/find-a-team/arjuna/?tab=members).

## References

- [NASA RHESSI Data Repository](https://hesperia.gsfc.nasa.gov/rhessi_data_search/rhessi_data_search_vme.html)
- [FITS Viewer and Tools](https://fits.gsfc.nasa.gov/fits_viewer.html)
- [Dataset Compilation Script](https://github.com/Jainish-Prajapati/Solar-Flare-Prediction/tree/main/Join_script)
- [Complete Dataset](https://github.com/Jainish-Prajapati/Solar-Flare-Prediction/tree/main/data)
