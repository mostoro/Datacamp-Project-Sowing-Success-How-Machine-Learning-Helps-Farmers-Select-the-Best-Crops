# Sowing Success: How Machine Learning Helps Farmers Select the Best Crops

This project uses machine learning to help farmers select the best crop for their fields based on essential soil metrics. By analyzing soil components such as nitrogen, phosphorus, potassium, and pH levels, we aim to predict the optimal crop that can thrive in a particular soil condition, maximizing yield and supporting efficient farm management.

## Project Files

- **`notebook.ipynb`**: Jupyter Notebook containing the full code, data analysis, and machine learning model for predicting the optimal crop based on soil conditions. The notebook walks through data exploration, feature selection, model building, and evaluation.
- **`soil_measures.csv`**: Dataset containing essential soil metrics and the corresponding optimal crop for each measurement. Columns include:
  - `N`: Nitrogen content in the soil
  - `P`: Phosphorus content in the soil
  - `K`: Potassium content in the soil
  - `pH`: pH value of the soil
  - `crop`: The crop that best suits the given soil conditions (target variable)

## Objective

The goal of this project is to build a multi-class classification model that can accurately predict the optimal crop based on soil metrics, helping farmers make informed decisions about crop selection.

## Instructions

1. **Load the Dataset**: Begin by loading `soil_measures.csv` into the notebook and exploring the data.
2. **Feature Engineering**: Analyze the soil metrics (N, P, K, and pH) to identify important features for crop prediction.
3. **Model Building**: Build a multi-class classification model using machine learning techniques to predict the best crop.
4. **Evaluation**: Evaluate the model’s performance and determine the most important soil feature for crop prediction.

## Results

The model's performance and key feature importance are detailed in `notebook.ipynb`. The analysis showed that potassium (`K`) was the most important factor in predicting the optimal crop.

## Requirements

- Python (version >= 3.6)
- Jupyter Notebook
- Required Python libraries:
  - `pandas`
  - `numpy`
  - `scikit-learn`

## Usage

Clone the repository and open `notebook.ipynb` to get started. Run the cells sequentially to load the data, train the model, and view results.

```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
jupyter notebook notebook.ipynb
