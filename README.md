# Time_Series_Forecasting

---

## 📊 Dataset

- **Features**:
  - PM2.5 concentration
  - Dew point
  - Temperature
  - Pressure
  - Wind direction & speed
  - Weather conditions

---

## 🧪 Problem Statement

Air pollution poses serious health risks. PM2.5 levels, in particular, are a major concern in urban environments like Beijing. This project uses time series forecasting techniques with LSTM to predict PM2.5 levels hours into the future.

---

## ⚙️ Preprocessing

- Handling missing values via linear interpolation
- Date-time conversion and indexing
- Feature scaling using `RobustScaler`
- Sequence generation using a sliding window approach

---

## 🧠 Model Architecture

- **Type**: LSTM (Long Short-Term Memory)
- **Layers**:
  - stacked LSTM layers
  - Dense output layer
- **Loss Function**: Mean Squared Error (MSE)
- **Optimizer**: Adam
- **Metrics**: MAE, RMSE

---

## 📈 Evaluation

The model was evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Square Error (RMSE)
- Visualization of predictions vs. actual PM2.5 values

---

## ✅ Results

The model was able to capture temporal patterns and produced reasonable forecasts for short-term PM2.5 concentrations.
