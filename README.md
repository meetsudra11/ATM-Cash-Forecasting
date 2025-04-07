# 💰 ATM Cash Withdrawal Forecasting (2017–2025)

# 🎯 Objective
The primary objective of this project is to forecast ATM cash withdrawals using various time series models. In a rapidly evolving financial ecosystem where digital payments such as UPI are on the rise, it is crucial to assess how the demand for physical cash is changing.
Forecasting ATM withdrawals is vital for several reasons:
🏦 Banking Operations: Helps banks optimize cash logistics, refill schedules, and ATM uptime.
📉 Declining Trends: Analyzing the shift from cash to digital payments helps banks plan infrastructure investments.

# 📦 Dataset Overview
The dataset used in this project was collected from the Reserve Bank of India's official website, covering the period from January 2017 to January 2025. It includes monthly cash withdrawal data across all private and public banks in India.
📂 fetchingdata.ipynb: Script to fetch and structure the raw data
🧹 processing.ipynb: Preprocessing pipeline to clean and prepare the data for analysis
📁 Final data saved as RBIDATA.csv

# 🧪 Methodology
The analysis was carried out specifically for Bank of Baroda (BOB), though the pipeline can be easily extended to other banks.
We explored and compared the performance of multiple models:
🔁 ARIMA – Captures linear temporal structures
🤖 LSTM – Deep learning model capable of modeling complex patterns
🔮 FBProphet – Handles trend, seasonality, and holiday effects (run both with and without holidays)

