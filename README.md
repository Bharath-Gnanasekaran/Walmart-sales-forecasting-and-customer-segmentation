# Walmart Sales Forecasting & Online Retail Customer Segmentation

**Author:** Bharath Gnanasekaran  

---

## 📌 Project Overview
This project solves two key business problems:

1. **Walmart Sales Forecasting**  
   - Forecast weekly sales for multiple Walmart stores.  
   - Helps in inventory planning and demand management.

2. **Online Retail Customer Segmentation**  
   - Analyze customer purchase behavior using RFM (Recency, Frequency, Monetary).  
   - Segment customers for targeted marketing.

---

## 🧰 Tech Stack
- Python, Pandas, NumPy, Matplotlib
- ARIMA / auto_arima (time series forecasting)
- K-Means clustering (customer segmentation)
- Jupyter / Google Colab
- Joblib (saving models)

---

## 📂 Files in this Repository

- `Capstone_Project_By_Bharath.ipynb` – Full notebook with EDA, forecasting and clustering.
- `Capstone_Project_By_Bharath.pdf` – Final project report.
- `Walmart_All_Stores_Forecast.csv` – 12-week ahead forecasts for all stores.
- `store*_forecast_model.pkl` – Saved ARIMA models.
- `rfm_scaler.pkl` & `rfm_kmeans.pkl` – Scaler and clustering model for RFM analysis.

---

## 📊 Key Insights

### Walmart
- Strong weekly seasonality in sales.
- Holiday periods show sales spikes.
- Store-wise differences can be used for localized planning.

### Online Retail
- A small set of customers drive high revenue.
- Clear segments such as loyal, recent, at-risk, and low-value customers.
- Marketing teams can create different campaigns based on RFM segments.

---

## 🚀 Future Improvements
- Use SARIMAX with external features (holiday flag, CPI, etc.).
- Try LSTM deep learning models for forecasting.
- Build an interactive Power BI / dashboard for business users.

---

## 📫 Contact

**Email:** bharathr8.bg@gmail.com  
**Location:** Trichy, Tamil Nadu, India
