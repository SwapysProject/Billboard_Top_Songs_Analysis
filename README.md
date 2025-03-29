# Billboard Top Songs - Peak Position Prediction

## 📖 Overview
This project involves predicting a song's **Peak Position** on music charts using various features such as genre, popularity metrics, and release details. The workflow includes **Exploratory Data Analysis (EDA)**, **Feature Engineering**, and **Model Training**.

## 📂 File Structure
- `music_dataset.csv`: Raw dataset.
- `EDA.py`: Script for exploratory data analysis.
- `Feature_Engineering.py`: Script for creating and selecting features.
- `Model_Training.py`: ElasticNet model training script.
- `Saved_Models/elasticnet.pkl`: Saved trained model.

## 🛠️ Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/yourrepo.git
cd yourrepo
```

### 2. Create a Virtual Environment (Optional)
```bash
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

**Required Libraries:**
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `joblib`
- `seaborn`
- `xgboost`

## 🔍 Exploratory Data Analysis (EDA)
The EDA script includes:
- **Summary Statistics:** Mean, median, mode.
- **Missing Value Analysis:** Null value handling.
- **Distribution Plots:** Histograms, box plots, violin plots.
- **Correlation Analysis:** Heatmaps to identify feature relationships.

### To run EDA:
```bash
python EDA.py
```

## 🏗️ Feature Engineering
The feature engineering script includes:
- **Handling Missing Values:** Imputation strategies.
- **Encoding Categorical Variables:** One-hot encoding, label encoding.
- **Feature Selection:** Correlation-based selection, feature importance.

### To run Feature Engineering:
```bash
python Feature_Engineering.py
```

## 🚀 Model Training
The model training script uses **ElasticNet Regression** with hyperparameter tuning via **GridSearchCV**. It evaluates performance using metrics like MAE, MSE, RMSE, and R².

### To run Model Training:
```bash
python Model_Training.py
```

## 📊 Model Performance
- **Mean Absolute Error (MAE):**  
- **Mean Squared Error (MSE):**  
- **Root Mean Squared Error (RMSE):**  
- **R-squared (R2):**  
 

## 📤 Exported Model
The final ElasticNet model is saved as a `.pkl` file:
```bash
Saved_Models/elasticnet.pkl

💬 Suggestions & Interaction

Suggestions, contributions, and advice are highly encouraged! I am willing to interact and collaborate with anyone interested in improving this project.