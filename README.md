# LSTM-
# India Weather Forecasting with LSTM

This project uses an LSTM model to predict the next year's average temperature using India's historical temperature data (1901–2017).

## 📊 Dataset
- Source: Provided dataset with monthly temps from 1901 to 2017
- Processed into average yearly temperature

## 🧠 Model
- LSTM with 64 units
- Dropout layer to avoid overfitting
- Dense layer outputs a temperature

## 🔍 Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- MAE and MSE during training

## 📈 Visualizations
- Training vs Validation Loss
- Training vs Validation MAE

## 🛠️ How to Run

```bash
pip install tensorflow pandas matplotlib scikit-learn
python weather_lstm.py
