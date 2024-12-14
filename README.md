# Agricultural Product Price Prediction

## 📌 Project Overview

This project aims to develop a machine learning model capable of predicting agricultural product prices using advanced data analysis and machine learning techniques.

## 🎯 Objectives

- Build an accurate predictive model for agricultural product prices
- Compare different machine learning techniques
- Provide a decision-support tool for farmers and traders

## 📦 Technical Requirements

### Environment
- Python 3.8+
- Jupyter Notebook or compatible IDE

### Dependencies
- numpy
- pandas
- matplotlib
- scikit-learn
- joblib
- seaborn
- openpyxl

## 🚀 Installation

1. Clone the repository
```bash
git clone https://github.com/Grand-Nord-Developpers-Community/live-coding-session-MachineLearning.git
cd agricultural-price-prediction
```

2. Install dependencies
```bash
pip install -r requirements.txt
```

## 📊 Project Contents

- `ecocrops_dataset.xlsx`: Agricultural prices dataset
- `Prediction Prix Produits agricole.ipynb`: Main Jupyter Notebook
- `best_price_prediction_model.joblib`: Exported model

## 🧠 Methodology

### Data Processing Steps
1. Data exploration
2. Preprocessing and encoding
3. Training and test data separation
4. Multiple model training
5. Comparative evaluation

### Evaluated Models
- Linear Regression
- Decision Tree
- Random Forest
- Gradient Boosting

## 📈 Model Performance

| Model | MSE | R² | Performance |
|-------|-----|-----|-------------|
| Linear Regression | 481,529.90 | 0.96% | Low |
| Decision Tree | 119,260.23 | 75.5% | Medium |
| Random Forest | 94,404.43 | 80.6% | Very Good |
| Gradient Boosting | 89,783.21 | 81.5% | Excellent |

## 🔍 Model Usage

```python
# Prediction example
predicted_price = predict_price(
    zone='MORA', 
    product='Rice', 
    month='April', 
    year=2024
)
```

## 🔮 Key Features

- Agricultural price prediction
- Price distribution analysis
- Trend visualization
- Best model export

## 📋 Limitations and Future Perspectives

- Current accuracy: ±3-8% of average prices
- Improvement areas:
  - Larger data collection
  - Integration of additional variables
  - Exploration of more advanced models

## 👥 Contributing

Contributions are welcome! Please follow these steps:
1. Fork the project
2. Create a feature branch
3. Commit your changes
4. Submit a pull request

## 📄 License

MIT 

## 🙏 Acknowledgments

- Development team
- Contributors
- Data sources
