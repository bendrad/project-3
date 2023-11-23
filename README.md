# project-3
# Predictive Regression Machine Learning on Daegu Apartment Data

This repository contains a Jupyter notebook that predicts property prices using the Gradient Boosting Regressor model. The model is trained with a dataset that includes features such as hallway type, time to subway, number of amenities nearby, year built, property size, and more.

## Project Description

This project aims to understand the factors that influence property prices and build a predictive model that can help prospective buyers or sellers in estimating market prices.

## Model Features

The model involves several stages of data preprocessing, including:
- Normalization of numerical features using `RobustScaler`
- Categorical feature encoding with `OneHotEncoder`
- Ordinal feature transformation using `OrdinalEncoder`
- Feature engineering to improve model performance

## Repository Structure
- `data_daegu_apartment.csv`: Dataset for model building process.
- `ML.ipynb`: Jupyter notebook with the entire analysis and model building process.
- `gbr_akbar.pkl`: Machine learning model that has been trained and stored.
- `requirements.txt`: List of dependencies required to run the notebook.

## How to Run the Notebook

1. Clone this repository to your local system.
2. Install the dependencies using the `pip install -r requirements.txt` command.
3. Open `ML.ipynb` using Jupyter Notebook or JupyterLab.
4. Run all cells in the notebook to see the analysis process and prediction results.

## Dependencies

- pycaret
- category_encoders
- scikit-learn
- scipy
- statsmodels
- pandas
- numpy
- matplotlib
- seaborn
- tabulate
- warnings
- time

## Contact
If you have any questions or would like to discuss further regarding this project, please feel free to contact me:

- Name: Akbar Rinaldi
- Email: akbarinaldi@gmail.com
- LinkedIn: https://www.linkedin.com/in/akbarinaldi/
- GitHub: https://github.com/bendrad

I am open to collaboration or if you would like to provide feedback to improve this project.
