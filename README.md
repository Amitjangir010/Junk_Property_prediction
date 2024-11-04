# 🏠 Property Junk Score Predictor

An advanced machine learning model that predicts the probability of a property being classified as "junk" based on various property characteristics and market indicators.

## 🎯 Project Overview

This project uses Random Forest classification to analyze property data and predict junk scores, helping real estate professionals and investors make informed decisions about property investments.

## 📊 Key Features

- **High Accuracy**: Achieves reliable prediction accuracy
- **Multiple Features**: Analyzes 30+ property characteristics
- **Market Indicators**: Incorporates 9 different price indices
- **Location Analysis**: Considers regional and state-level factors
- **Temporal Analysis**: Includes build year and property age

## 🔍 Feature Categories

### Property Characteristics
- Interior Style
- Material
- Facade Color
- Build Year
- Property Age

### Location Metrics
- State
- Region
- Region Type
- Normalized Population
- Area Income Type

### Market Indicators
- Price Index (1-9)
- Environmental Rating
- Agency Category

## 💻 Technical Details

### Tech Stack
- **Python 3.11+**
- **Key Libraries**:
  - Pandas for data manipulation
  - NumPy for numerical operations
  - Scikit-learn for machine learning
  - Matplotlib/Seaborn for visualization

### Model Pipeline
1. **Data Preprocessing**
   - Missing value handling
   - Feature encoding
   - Data normalization

2. **Feature Engineering**
   - Date processing
   - Categorical encoding
   - Feature scaling

3. **Model Training**
   - Random Forest Classifier
   - Hyperparameter tuning
   - Cross-validation

## 📈 Sample Output
```python
predictions = model.predict_proba(property_data)
# Output: Probability score between 0-1
# Example: 0.234 (23.4% probability of being junk)
```

## 🚀 How to Use

1. Clone the repository:
```bash
git clone https://github.com/Amitjangir010/Junk_Property_prediction.git
```
2. Run the notebook:
```bash
jupyter notebook Junk_Property.ipynb
```

## 📊 Data Structure

```
Property_train.csv
├── InteriorsStyle
├── PriceIndex (1-9)
├── Material
├── Agency
├── AreaIncomeType
└── ...other features
```
---
Made with ❤️ by Amit Jangir
