# Multivariate Time Series Forecasting using Long Short Term Memory (LSTM)

**Watch the demo on YouTube: https://youtu.be/D6i254GzW6w**

**[View the Jupyter Notebook for this project](https://github.com/ashwinravrao/Deep-Learning-Weather-Forecast/blob/master/AshwinRao_CSC578710_Final.ipynb)**

**Problem:** Using historical weather data, predict the next hour's temperature from the previous 24 hours' climate and temperature readings. The data contain 14 quantitative variables and 1 String timestamp. We will be primarily using Long-Short-Term Memory neurons for this forecasting problem. We will also experiment with multiple dense layers, as is somewhat standard fare in the literature.

**Variables:**

- Date Time
- Atmospheric Pressure (p (mbar))
- Temperature in Celsius (T (degC)) <-- target (what we will predict)
- Potential Temperature (Tpot (K))
- Dew Point Temperature (Tdew (degC))
- Relative Humidity (rh (%))
- Saturation Water Level Pressure (VPmax (mbar))
- Actual Water Level Pressure (VPact (mbar))
- Water Level Pressure Deficit (VPdef (mbar))
- Specific Humidity (sh (g/kg))
- Water Vapor Concentration (H2OC (mmol/mol))
- Air Density (rho (g/m\**3))
- Wind Velocity (wv (m/s))
- Maximum Wind Velocity (max. wv (m/s))
- Wind Direction (wd (deg))

**Strategy:** Build a base model that incorporates at least 1 LSTM layer (and possibly some dense layers). Then, if the model is learning appropriately and the error term is low enough, we can begin hyperparameter/parameter tuning.

**Scoring:** Mean Absolute Error (MAE)

---
Final deep learning project for CSC 578 (Neural Networks and Deep Learning)
