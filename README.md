# 📈 Electric Vehicle (EV) Adoption Forecasting

This project analyzes and forecasts Electric Vehicle (EV) adoption trends in Washington State using publicly available datasets. It involves data preprocessing, exploratory data analysis (EDA), and time series forecasting.

---

## 📂 Project Structure

```
├── EV_Adoption.ipynb                        # Jupyter Notebook for data analysis and forecasting
├── Electric_Vehicle_Population_By_County.csv  # Raw dataset containing EV registrations
├── preprocessed_ev_data.csv                 # Cleaned and aggregated dataset
├── forecasting_ev_model.pkl                 # Trained forecasting model (Pickle format)
├── README.md                                # Project documentation
```

---

## 📊 Dataset

* **Source:** Washington State Department of Licensing
* **File:** `Electric_Vehicle_Population_By_County.csv`
* **Content:** EV details including county, city, model year, make, model, and vehicle type.

---

## 🔧 Preprocessing Steps

* Filtered for active EVs only
* Converted date formats and extracted useful time features
* Aggregated data monthly for forecasting
* Saved as `preprocessed_ev_data.csv`

---

## 📈 Forecasting

* **Approach:** Time Series Forecasting
* **Model Used:** ARIMA / Prophet / (Specify actual model used)
* **Output:** Trained model file `forecasting_ev_model.pkl`
* **Goal:** Predict future EV registrations based on historical trends

---

## 📒 Notebook Highlights

* Data cleaning and feature engineering
* Trend and seasonality analysis
* Forecast visualization
* Model evaluation metrics (e.g., MAE, RMSE)

---

## 📌 Requirements

* Python 3.8+
* pandas, matplotlib, seaborn
* scikit-learn, statsmodels / Prophet
* jupyter, pickle

---

## 📈 Output Example

* Line plot showing historical and predicted EV adoption
* Trend and seasonal decomposition charts

---

## 🤝 Contributing

Feel free to fork the repo and submit pull requests. For major changes, please open an issue first.

---

## 📄 License

[MIT](https://choosealicense.com/licenses/mit/)

---

