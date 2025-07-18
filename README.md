# California Housing Price Prediction 🏡

This project is a complete **end-to-end machine learning pipeline** to predict housing prices in California.

## 🎯 Objective

Build a regression model to predict median house values based on California census data. The project explores, processes, and models real-world data using an industry-grade ML pipeline.

## 📊 Project Highlights

- 🧹 **Data Cleaning & Missing Value Imputation**
- 🏗️ **Feature Engineering** (e.g., ratios, log transformation, geographical clustering)
- 🔧 **Custom Transformers & Pipelines using `FunctionTransformer`**
- 🧠 **Model Comparison**: Linear Regression, Decision Tree, and Random Forest
- 🔁 **Cross-Validation & Evaluation using RMSE**
- 🌲 **Final model selection: Random Forest Regressor**
- 📈 **Rich Visualizations** using Matplotlib/Seaborn

## 🧪 Models Used

| Model                   | Description                                              |
|-------------------------|----------------------------------------------------------|
| **Linear Regression**   | Simple baseline model for comparison                     |
| **Decision Tree Regressor** | Captures non-linear patterns, but prone to overfitting    |
| **Random Forest Regressor** | Final chosen model due to better generalization            |

All models were trained using the same preprocessing pipeline and evaluated using **cross-validated RMSE (CV=10)**.

## 📷 Visualizations

Stored in:  
```
images/end_to_end_project/
```

Includes:
- Feature histograms
- Scatter plots with geographical data
- Long tail transformations
- Categorical bar charts
- Similarity-based cluster visualizations

## 🚀 How to Run

### 1. Clone the Repo
```bash
git clone https://github.com/AriseAk/AIML.git
cd AIML
```

### 2. (Optional) Create a virtual environment
```bash
python -m venv venv
venv\Scripts\activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Open the notebook
```bash
jupyter notebook housing.ipynb
```

## ⚠️ Note on Model File

The trained model file (`my_california_housing_model.pkl`) is not included due to GitHub's file size limit (100 MB).  
You can retrain and save it locally using the final cells in the notebook.

## 🧰 Tools & Libraries

- Python 3.10+
- Jupyter Notebook
- Scikit-Learn
- NumPy / Pandas
- Matplotlib / Seaborn


