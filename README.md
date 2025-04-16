
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
   Open the `Classification_CW.ipynb` notebook and follow the instructions to predict passenger survival.

2. **Run the Regression Model on California Housing Dataset:**
   Open the `regression_CW.ipynb` notebook and follow the instructions to predict house values.

## Contributing
Feel free to fork the project and submit pull requests if you'd like to contribute to the codebase. Please open issues if you encounter bugs or have feature requests.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
