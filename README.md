# Weather Forecasting using SARIMA

This project demonstrates how to use the **Seasonal AutoRegressive Integrated Moving Average (SARIMA)** model to forecast temperature patterns based on historical weather data using Python.

## 📈 Key Features
- Time series analysis and visualization
- SARIMA model fitting and evaluation
- Forecasting future values with confidence intervals
- Plotting and diagnostic checking

## 🧪 Technologies Used
- Python 3
- `pandas`, `numpy` for data handling
- `matplotlib`, `seaborn` for visualization
- `statsmodels` for SARIMA modeling

## 📂 Project Structure
```
.
├── 10. Sarima_weather.ipynb   # Main notebook
├── README.md                  # Project overview
├── LICENSE                    # MIT License
└── .gitignore                 # Git exclusions
```

## 🔍 Highlights

- **Decomposition of time series** to observe trend and seasonality
- **SARIMA Model Parameters**: (p,d,q)(P,D,Q,s)
- **Model diagnostics**: residual plots and AIC/BIC comparison
- **Forecasting**: future temperature predictions with upper/lower bounds

## 📊 Example Output (Synthetic Visualization)
```
Temperature Forecast
|----------------------|
| Date       | Temp    |
|------------|---------|
| 2025-01-01 | 28.6°C  |
| 2025-01-02 | 29.1°C  |
| 2025-01-03 | 27.8°C  |
```

## ▶️ How to Use

1. Open the Jupyter notebook `10. Sarima_weather.ipynb`
2. Ensure required libraries are installed:
```bash
pip install pandas numpy matplotlib seaborn statsmodels
```
3. Run the notebook cells sequentially to visualize data, train the model, and generate forecasts.

## 📄 License
MIT License © 2025 Md. Akiful Hoque Akif

## 🙋‍♂️ Author
Md. Akiful Hoque Akif  
[GitHub Profile](https://github.com/mdakif5717)
