# national-grid-forecasting
15-year UK electricity demand analysis and forecasting project.

# UK National Grid Electricity Demand Forecasting

This project explores 15 years of UK National Grid electricity demand data, with the goal of understanding seasonal trends and building time series forecasting models. The project includes data cleaning, exploratory analysis, and forecasting using Prophet, XGBoost, and LSTM.

## 📊 Overview

- Dataset: UK National Grid electricity demand (2008–2023)
- Tools: Python, Pandas, Prophet, XGBoost, TensorFlow/Keras
- Focus: Forecasting electricity demand using different ML and DL approaches

## 🔍 Project Structure

- `notebooks/`: Main Jupyter notebook with full analysis and models
- `outputs/`: Forecast plots and figures
- `requirements.txt`: Python libraries used

## 🧠 Key Findings

- **Prophet** performed best for seasonal forecasting with minimal tuning.
- **XGBoost** required significant feature engineering to approximate seasonal patterns.
- **LSTM** showed instability due to the dataset size, with results varying between runs.

## 🗂 How to Use

1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/national-grid-forecasting.git
    cd national-grid-forecasting
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Open the notebook:
    ```bash
    jupyter notebook notebooks/national_grid_forecasting.ipynb
    ```

## 📽 Presentation

A short 10-minute presentation summarizing the results is available (http://docs.google.com/presentation/d/1K2tZQLa5d1jEXbNu7SjzVQpgywQ0sdxQesYwqyDjLPc/edit?usp=sharing)

## 📄 License

This project is licensed under the MIT License. See `LICENSE` for details.
