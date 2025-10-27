# Telecom-Italia-Milan-Internet-Usage-Analysis

### Overview

This project focuses on analyzing and forecasting internet usage patterns from the Telecom Italia Milan dataset.
It applies data preprocessing, outlier removal, and time-series modeling using a SARIMA model optimized through Grid Search to capture seasonal and trend behaviors in network demand.

### Key Steps

- Data loading and cleaning from multiple text files

- Aggregation by datetime, cell ID, and country code

- Outlier detection and removal using IQR

- Handling missing data through temporal averaging

- Stationarity testing with the Augmented Dickey-Fuller (ADF) test

- Time-series resampling and decomposition

- SARIMA model building and hyperparameter tuning via Grid Search

- Forecasting and performance evaluation using AIC and MAPE

### Tools and Libraries

Python, Pandas, NumPy, Matplotlib, Seaborn, Statsmodels, Scikit-learn, TQDM

### Usage

**1. Clone the repository**
```
git clone https://github.com/yourusername/telecom-italia-usage-analysis.git
cd telecom-italia-usage-analysis
```

**2. Install dependencies**
```
pip install -r requirements.txt
```

**3. Run the Jupyter notebook**
```
jupyter notebook Telecom_Italia_Milan_Usage_Analysis.ipynb
```
### Result

The optimized SARIMA model successfully forecasts internet traffic, revealing clear daily and seasonal patterns in user activity across the Milan telecom network.
