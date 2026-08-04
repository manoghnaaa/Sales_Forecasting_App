# Sales Forecasting App 📈

An interactive Streamlit dashboard designed to forecast monthly shampoo sales using an ARIMA (AutoRegressive Integrated Moving Average) time series model. 

## 🚀 Live Demo
Once deployed, this app runs live on Streamlit Community Cloud.

## 🛠️ Features
- **Interactive Projections**: Forecast shampoo sales up to 24 months into the future using a slider control.
- **Dynamic Metrics**: Highlights the last actual sales figure, the next month's forecast, and the overall trend percentage.
- **Plotly Visualizations**: Interactive time series chart comparing historical actual sales with future projected forecast lines.
- **Data Explorer & Export**: View the raw forecast numbers in a table and download them as a CSV file.

## 💻 Tech Stack
- **Dashboard**: Streamlit
- **Forecasting Model**: Statsmodels ARIMA (5, 1, 0)
- **Data Wrangling**: Pandas, NumPy
- **Interactive Plotting**: Plotly

## ⚙️ Running Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/manoghnaaa/Sales_Forecasting_App.git
   cd Sales_Forecasting_App
   ```
2. Re-create and activate virtual environment:
   ```bash
   python -m venv venv
   .\venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Start the dashboard:
   ```bash
   streamlit run app.py
   ```
