# World Happiness Analysis

## Project Description

This project utilizes world happiness data to develop and evaluate three machine learning models:

1. Linear Regression
2. Random Forest Regressor
3. Random Forest Classifier

The data is contained in the `data/archive` folder, but ideally, it should be stored in a database for easier management and access.

## Requirements

### Library Installation

It is recommended to use a virtual environment to manage the project's dependencies. To create and activate a virtual environment, you can use the following commands:

```bash
# Create a virtual environment
python -m venv env

# Activate the virtual environment on Windows
.\env\Scripts\activate

# Activate the virtual environment on macOS/Linux
source env/bin/activate
```

Once the virtual environment is activated, install the required libraries using `pip`:

```bash
pip install -r requirements.txt
```

### Data

Ensure the data files are located in the `data/archive` folder. The data should include CSV files for the years 2015 to 2019.

## Running the Project

To run the project, execute all the cells from top to bottom in the `regression_and_classification.ipynb` Jupyter Notebook. This notebook contains all the necessary steps for data preprocessing, model training, evaluation, and feature importance analysis.

### Models Used

1. **Linear Regression**: Used to predict the happiness score based on various socio-economic factors.
2. **Random Forest Regressor**: Another model used to predict the happiness score with potentially better accuracy and handling of non-linear relationships.
3. **Random Forest Classifier**: Used to classify countries into different happiness categories (High, Medium, Low) based on the happiness score.


If you encounter any issues or have questions, feel free to open an issue or contact the project maintainer.
