# **TimeGPT Usage Summary**

This summary provides an overview of the various tasks performed using the `TimeGPT` and `NixtlaClient` libraries for time series forecasting and analysis.

---

## **Tasks Completed**

### 1. **Multivariate Time Series Forecasting**
   - **Goal:** Forecast multiple time series simultaneously with a focus on handling related features.
   - **Steps:**
     - Loaded synthetic multivariate data (e.g., Passengers, Scaled Passengers, Trends).
     - Used the `forecast` method to predict future values for all series.
     - Visualized the results using Matplotlib to compare actual and forecasted values.

---

### 2. **Fine-Tuning the Model**
   - **Goal:** Improve forecasting accuracy by fine-tuning the model on recent data.
   - **Steps:**
     - Used the `finetune_steps` parameter in the `forecast` method to apply fine-tuning.
     - Trained the model on training data and forecasted on unseen test data.
     - Evaluated the performance and visualized the results.

---

### 3. **Anomaly Detection**
   - **Goal:** Detect anomalies in a univariate time series.
   - **Steps:**
     - Used the `detect_anomalies` method to flag anomalies in a time series.
     - Applied confidence levels to determine the sensitivity of anomaly detection.
     - Highlighted anomalies on a plot for better visualization.

---

### 4. **Energy Demand Forecasting**
   - **Goal:** Predict future energy demand using historical data.
   - **Steps:**
     - Loaded synthetic energy data (e.g., temperature and scaled temperature).
     - Forecasted energy demand for the next 30 days using the `forecast` method.
     - Plotted historical data alongside predictions.

---

### 5. **Bitcoin Price Forecasting**
   - **Goal:** Predict future Bitcoin prices using historical market data.
   - **Steps:**
     - Downloaded historical price data for Bitcoin using the `yfinance` library.
     - Cleaned and formatted the data to match TimeGPT's requirements.
     - Used the `forecast` method to predict Bitcoin prices for the next 30 days.
     - Visualized the forecasted prices alongside historical data.

---

## **Link to Nixtla Documentation**
For more details about the `TimeGPT` and `NixtlaClient` functionalities, refer to the [Nixtla Documentation](https://docs.nixtla.io/).
