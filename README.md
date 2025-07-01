# Predictive Analysis - Prediction of Peak Time

## 📊 Project Overview

This project implements a comprehensive predictive analysis system to forecast peak usage times based on system performance metrics. The analysis uses machine learning algorithms to predict when system resources will experience high demand, enabling proactive resource management and capacity planning.

## 🎯 Key Features

- **Time Series Analysis**: Analyzes historical system metrics to identify patterns
- **Peak Time Prediction**: Predicts when system usage will reach peak levels
- **Multiple ML Models**: Implements various machine learning algorithms for comparison
- **Real-time Monitoring**: Provides insights for proactive system management
- **Holiday Impact Analysis**: Considers holiday effects on system usage patterns

## 📁 Project Structure

```
├── predictiveanalysis.ipynb          # Main analysis notebook
├── predictiveanalysis-hourly.ipynb   # Hourly analysis notebook
├── metrics_data.csv                  # Main dataset (10,000+ records)
├── metrics_data_1000.csv             # Sample dataset (1,000 records)
├── metrics_data_20000.csv            # Extended dataset (20,000+ records)
├── metrics_hourly_last_365_days.csv  # Hourly data for last 365 days
├── requirements.txt                  # Python dependencies
└── readme.md                         # Project documentation
```

## 📈 Data Features

The analysis uses the following system metrics:

- **timestamp**: Time of measurement
- **cpu_usage**: CPU utilization percentage
- **memory_usage**: Memory utilization percentage
- **load_capacity**: System load capacity (0-1 scale)
- **error_rate**: Error rate percentage
- **throughput**: System throughput metrics
- **is_holiday**: Binary indicator for holiday periods

## 🛠️ Technologies Used

### Core Libraries
- **pandas** (1.5.3) - Data manipulation and analysis
- **numpy** (1.24.3) - Numerical computing
- **scikit-learn** (1.2.2) - Machine learning algorithms
- **tensorflow** (2.12.0) - Deep learning framework
- **xgboost** (1.7.6) - Gradient boosting algorithms

### Visualization & Analysis
- **matplotlib** (3.7.1) - Data visualization
- **seaborn** (0.12.2) - Statistical data visualization
- **statsmodels** (0.13.5) - Statistical analysis

### API & Deployment
- **fastapi** (0.68.1) - Web API framework
- **uvicorn** (0.15.0) - ASGI server
- **pydantic** (1.8.2) - Data validation

### Additional Tools
- **yfinance** (0.2.35) - Financial data access
- **cmdstanpy** (≥1.1.0) - Bayesian analysis

## 🚀 Installation & Setup

### Prerequisites
- Python 3.8 or higher
- pip package manager

### Installation Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/techworldwithgeeta/PredctiveAnalysis-Prediction-of-Peak-Time.git
   cd PredctiveAnalysis-Prediction-of-Peak-Time
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

## 📖 Usage

### Running the Analysis

1. **Open the main notebook**:
   - `predictiveanalysis.ipynb` - Complete analysis with all models
   - `predictiveanalysis-hourly.ipynb` - Focused on hourly predictions

2. **Execute cells sequentially** to:
   - Load and preprocess data
   - Perform exploratory data analysis
   - Train machine learning models
   - Evaluate model performance
   - Generate predictions

### Key Analysis Components

- **Data Preprocessing**: Cleaning, normalization, and feature engineering
- **Exploratory Data Analysis**: Statistical insights and visualizations
- **Model Training**: Multiple algorithms including:
  - Linear Regression
  - Random Forest
  - XGBoost
  - Neural Networks
  - Time Series Models
- **Model Evaluation**: Performance metrics and comparison
- **Prediction Generation**: Future peak time forecasts

## 📊 Model Performance

The project evaluates models using various metrics:
- **Mean Absolute Error (MAE)**
- **Root Mean Square Error (RMSE)**
- **R-squared (R²)**
- **Mean Absolute Percentage Error (MAPE)**

## 🔮 Prediction Capabilities

- **Short-term predictions**: Next few hours
- **Medium-term forecasts**: Daily and weekly patterns
- **Seasonal analysis**: Holiday and weekend effects
- **Anomaly detection**: Unusual usage patterns

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👨‍💻 Author

**Geeta** - [techworldwithgeeta](https://github.com/techworldwithgeeta)

## 🙏 Acknowledgments

- Data science community for best practices
- Open-source contributors for the libraries used
- System administrators for domain expertise

## 📞 Support

For questions or support, please open an issue in the GitHub repository or contact the author.

---

**Note**: This project is designed for educational and research purposes. Always validate predictions in your specific environment before making operational decisions.

 
