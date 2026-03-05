# Stock_Market_Predictor: Machine Learning & Macro Anaysis

! [S&P 500 Trend](social_preview.png)

## Description:
This project uses **Machine Learning** algorithms to analyze the historical trends of the S&P 500 index and predict future movement. The model integrates financial data with macroeconomic indicators sourced from the **FRED** (Federal Reserve Economic Data) API.

## Key Features:
- **Directional Prediction**: Uses classification models to predict market trends (Up/Down).
- **API Integration**: Dynamic connection with the FRED Database for real-time macro data.
- **Secure Management**: Implementation of environment variables ('.env') to protect personal API keys.
- **Data Visualization**: Detailed historical and predective charts created with Matplotlib.

## Technologies used:
- **Python 3**
- **Pandas** & **NumPy** (Data Manipulation)
- **Scikit-learn** (Machine Learning)
- **Matplotlib** (Data Visualization)
- **python-dotenv** (Credential Security)

## Local configurtion:
To protect privacy, API keys are not included in this public repository.
1. Create a '.env' file in the root directory.
2. Add your FRED API key: 'APIKEY=your_fred_key_here'
3. The '.gitignore' file is already configured to keep your secrets safe.

---
*Project created for statistical analysis and educational purposes.*
