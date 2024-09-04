# Weather Forecasting Model
This repository contains a machine learning model designed to predict weather conditions based on historical weather data. The model uses features such as precipitation, maximum temperature, minimum temperature, and wind speed to predict the weather type.

## Tech Stack
1. Python
2. Jupyter Notebook
3. Pandas
4. NumPy
5. Matplotlib & Seaborn
6. Scikit-learn
7. Pickle

These can be installed using pip:<br>*pip install pandas numpy matplotlib seaborn scikit-learn missingno*

## Repository Structure
- **dataset.csv**<br>This CSV file contains the historical weather data used to train and evaluate the model. The dataset consists of 1,461 entries with the following columns:
  - date: The date of the weather observation.
  - precipitation: The amount of precipitation in mm.
  - temp_max: The maximum temperature recorded on that day (in degrees Celsius).
  - temp_min: The minimum temperature recorded on that day (in degrees Celsius).
  - wind: The wind speed recorded on that day (in m/s).
  - weather: The observed weather condition (e.g., rain, drizzle).

- **src.ipynb**<br>This notebook contains the code for data preprocessing, feature engineering, and model training. It also includes the model evaluation and the generation of classification reports.

- **TestRun.ipynb**<br>This notebook demonstrates how to load the trained model and use it for making predictions on new data. It contains interactive input cells where users can input weather parameters (precipitation, maximum temperature, minimum temperature, wind) to get a predicted weather condition.

- **env/**<br>This folder contains the virtual environment setup for the project. It includes all the necessary dependencies and packages required to run the notebooks and scripts in this repository. Activate this environment to ensure all dependencies are correctly installed.

- **model.pkl**<br>This file contains the trained machine learning model saved in a serialized format using pickle. This model is loaded in the TestRun.ipynb notebook to make predictions on new weather data.

## Usage
### Training the Model
  1. Clone the repository and navigate to the project directory.
  2. Open src.ipynb in Jupyter Notebook or any compatible environment.
  3. Follow the steps in the notebook to preprocess the data and train the model.
  4. The trained model will be saved as a .pkl file for future use.
### Making Predictions
  1. Open TestRun.ipynb in Jupyter Notebook.
  2. Load the trained model.
  3. Input the weather parameters when prompted.
  4. The model will output a predicted weather condition.

## Dataset
The dataset used for this model is included in this repository as dataset.csv. It contains weather observations over several years, providing a robust dataset for training a predictive model.

## Model
The model is trained using a machine learning approach, which includes feature selection and classification techniques. The notebook src.ipynb details the model architecture and evaluation metrics.

## Thank You : )

