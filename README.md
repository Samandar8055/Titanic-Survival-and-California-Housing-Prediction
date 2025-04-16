
# Titanic Survival and California Housing Prediction

## Overview
This repository contains the implementation of classification and regression models using the **Titanic dataset** and the **California housing dataset**.

- The **Titanic dataset** is used to predict passenger survival using classification models.
- The **California housing dataset** is used to predict the average house values in California districts using regression models.

### Classification Models for Titanic Dataset:
- **Random Forest Classifier (RFC)**
- **Logistic Regression**
- **Support Vector Machine (SVM)**

### Regression Models for California Housing Dataset:
- **Support Vector Regression (SVR)** 
- **Linear Regression**
- **Random Forest Regression (RFR)**

This project compares the performance of these models and demonstrates their prediction accuracy.

## Results

### Titanic Dataset Classification: Predicted vs Actual
Here’s a plot showing the comparison of predicted vs actual values for the classification task:

![Predicted vs Actual Titanic Classification](predicted%20vs%20acctual.png)

### California Housing Dataset Regression: Predicted vs Actual
Below are the results for different regression models comparing predicted vs actual values:

![SVR: Predicted vs Actual](actual%20vs%20predict%20dots.png)

### Error Rates of Different Regression Models
The following plot shows the error rates (Mean Squared Error) of different regression models:

![Error Rates of Different Models](error%20rate.png)

### Feature Distribution for California Housing Dataset
Here’s the distribution of features in the California housing dataset:

![Feature Distribution](Reg_plt.png)

## Installation
To set up the project, follow these steps:

### Clone the Repository
```bash
git clone https://github.com/your-username/Titanic-Survival-and-California-Housing-Prediction.git
```

### Install Dependencies
Ensure you have the necessary Python packages. You can install them via `pip` by running:
```bash
pip install -r requirements.txt
```

## Project Structure
The project is organized into the following main parts:

```
/Titanic-Survival-and-California-Housing-Prediction
    |-- Classification_CW.ipynb              # Titanic dataset classification notebook
    |-- regression_CW.ipynb                 # California housing dataset regression notebook
    |-- classification.csv                   # Titanic dataset CSV
    |-- regression.csv                       # California housing dataset CSV
    |-- requirements.txt                    # Python dependencies file
    |-- README.md                           # Project documentation (this file)
    |-- .gitignore                          # Gitignore file for ignored files (e.g., venv, cache)
```

## Usage
1. **Run the Classification Model on Titanic Dataset:**
   Open the `classification.ipynb` notebook and follow the instructions to predict passenger survival.

2. **Run the Regression Model on California Housing Dataset:**
   Open the `regression.ipynb` notebook and follow the instructions to predict house values.

## Contributing
Feel free to fork the project and submit pull requests if you'd like to contribute to the codebase. Please open issues if you encounter bugs or have feature requests.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
