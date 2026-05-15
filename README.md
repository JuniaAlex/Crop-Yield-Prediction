# 🌾 Crop Yield Prediction Based on Weather Data

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

## 📌 Overview

This project predicts **crop yield (tons/hectare)** using weather and soil features. It demonstrates a complete machine learning pipeline — from data generation and exploratory data analysis to model training, evaluation, and comparison.

## 🎯 Objective

Build and compare regression models to accurately predict crop yield based on environmental and agricultural features such as temperature, rainfall, soil nutrients (NPK), and seasonal patterns.

## 📂 Project Structure

```
Crop-Yield-Prediction/
├── cropyieldprediction.ipynb   # Main Jupyter Notebook
├── requirements.txt            # Python dependencies
├── LICENSE                     # MIT License
└── README.md                   # Project documentation
```

## 🔬 Methodology

### 1. Data Generation
- Synthetic dataset simulating real agricultural conditions
- Can be replaced with real-world datasets (e.g., from Kaggle)

### 2. Exploratory Data Analysis (EDA)
- Yield distribution analysis
- Seasonal yield patterns (violin plots)
- Correlation heatmaps for feature relationships
- Statistical summaries

### 3. Feature Engineering & Preprocessing
- Interaction features (e.g., `Temp × Rainfall`)
- Aggregate nutrient features (`NPK_total`)
- Standard scaling for numerical features
- Train/test split (80/20)

### 4. Model Training & Evaluation
The following models are trained and compared:

| Model | Description |
|-------|-------------|
| **Linear Regression** | Baseline linear model |
| **Ridge Regression** | L2-regularized linear model |
| **Random Forest** | Ensemble of 200 decision trees |

### 5. Metrics
- **MAE** (Mean Absolute Error)
- **RMSE** (Root Mean Squared Error)
- **R² Score** (Coefficient of Determination)

## 🛠️ Tech Stack

- **Python 3.8+**
- **NumPy** — Numerical computations
- **Pandas** — Data manipulation & analysis
- **Matplotlib & Seaborn** — Data visualization
- **Scikit-Learn** — Machine learning models & evaluation

## 🚀 Getting Started

### Prerequisites
```bash
pip install -r requirements.txt
```

### Run the Notebook
```bash
jupyter notebook cropyieldprediction.ipynb
```

Or open it directly in **Google Colab**, **Kaggle**, or **VS Code**.

## 📊 Sample Visualizations

The notebook includes:
- 📈 Yield distribution histograms with KDE
- 🎻 Violin plots for seasonal yield comparison
- 🔥 Correlation heatmaps
- 📊 Model comparison bar charts

## 🤝 Contributing

Contributions are welcome! Feel free to:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Junia Alex**
- GitHub: [@JuniaAlex](https://github.com/JuniaAlex)
