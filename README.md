# Stock Analysis and Price Prediction Model

## Overview
This project involves the analysis of stock prices of companies listed on Yahoo Finance, followed by the creation of a predictive model to forecast future stock prices. The model leverages the Long Short-Term Memory (LSTM) method, which is particularly effective for time series forecasting.

## Key Features
- **Stock Analysis:** Performed in-depth analysis on the historical stock prices of three companies: UPST, PFE, and ADBE.
- **Price Prediction:** Developed an LSTM-based model to predict the future prices of ADBE and PFE stocks.
- **High Accuracy:** Achieved remarkable prediction accuracies of **96.05%** for ADBE and **96.81%** for PFE.

## Data Sources
- The stock price data was sourced from [Yahoo Finance](https://finance.yahoo.com/), ensuring the use of reliable and up-to-date financial information.

## Methodology
1. **Data Collection:** Gathered historical stock price data for the selected companies.
2. **Data Preprocessing:** Cleaned and normalized the data to prepare it for model training.
3. **Model Development:** Used LSTM, a type of Recurrent Neural Network (RNN), which is well-suited for predicting sequences of data.
4. **Model Evaluation:** Tested the model on ADBE and PFE, resulting in high prediction accuracies of **96.05%** and **96.81%** respectively.

## Results
- **ADBE Stock:** The model successfully predicted future prices with an accuracy of **96.05%**.
- **PFE Stock:** The model achieved a prediction accuracy of **96.81%**, demonstrating its robustness.

## Conclusion
This project demonstrates the effectiveness of using LSTM for stock price prediction, providing highly accurate forecasts. The results indicate that this approach can be reliably used for financial forecasting in real-world scenarios.

## Installation & Usage
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/stock-analysis-and-price-prediction-model.git
    cd stock-analysis-and-price-prediction-model
    ```
2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the analysis and prediction script:
    ```bash
    python python_project_3.py
    ```

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
