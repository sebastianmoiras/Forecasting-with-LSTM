## Project Description
This project applies **Long Short-Term Memory (LSTM)** networks to forecast **Ambient Temperature (AT, °C)** as a time series prediction task.  

The dataset contains environmental and air quality features such as PM2.5, NO2, SO2, CO, etc.
The objective is to capture temporal dependencies and provide accurate forecasts of AT Degree °C.  

---

## Exploratory Data Analysis
Visualization of AT temperature trends and seasonality using STL decomposition:  

![STL Decomposition](/assets/stl.png)

---

## Model Training
The best-performing LSTM model shows the following training vs validation loss curve:  

![LSTM Loss Curve](/assets/loss_lstm.png)

---

## Forecasting Results
The model was evaluated on unseen sequences of AT (°C).  
Below is the result:  

![LSTM Forecast Result](/assets/result_lstm.png)

---

## Tech Stack
- **NumPy, Pandas, Scikit-learn**
- **TensorFlow / Keras**
- **Matplotlib, Seaborn**
