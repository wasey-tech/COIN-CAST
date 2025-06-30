# COIN-CAST
This project leverages machine learning techniques to anticipate future fluctuations in the prices of digital currencies. By analyzing historical market trends and technical indicators, the system aims to generate accurate forecasts that can aid in strategic crypto trading and investment decisions.

# 🔮 Crypto Market Forecasting (Using Binance API + Linear Regression)

This is a GUI-based Python project that fetches real-time cryptocurrency prices (BTC, DOGE, LTC) using the Binance API and predicts the next 10 days’ prices using Linear Regression. Built with **Tkinter**, **scikit-learn**, and **Matplotlib**, it offers a clean interface to visualize live data, train models, and display predictions.

---

## 🚀 Features

- 📡 **Live Crypto Price Fetching** – Get real-time prices of BTC, DOGE, and LTC from Binance API.
- 📈 **Visual Price Graphs** – Plot current crypto prices with clear line charts.
- 🔮 **Next 10-Day Forecast** – Uses Linear Regression to predict future prices.
- 📊 **Model Evaluation** – Shows MSE, MAE, and R² score for performance.
- 🪟 **Tkinter GUI** – Interactive desktop application with button-based control.

---

## 🧠 Tech Stack

- **Python 3.x**
- **Tkinter** – For GUI
- **Requests** – To call Binance API
- **NumPy, Pandas** – For data manipulation
- **scikit-learn** – For Linear Regression modeling
- **Matplotlib** – For plotting graphs

---

## 📦 File Structure

Crypto-Forecasting/
│
├── fina.py # Main Python GUI Application
├── requirements.txt # Python dependencies
├── .gitignore # Files/folders to exclude from Git
├── README.md # This file

yaml
Copy code

---

## ⚙️ Setup Instructions

Follow these steps to run the project locally:

### ✅ Step 1: Install Anaconda (if not already)

- Download from: [https://www.anaconda.com/products/distribution](https://www.anaconda.com/products/distribution)
- Install Python 3.x version during setup.

---

### ✅ Step 2: Create and Activate Virtual Environment

Open Anaconda Prompt and run:

```bash
conda create -n tf python=3.10
conda activate tf
✅ Step 3: Clone or Download the Project Files
If downloaded manually, extract to your desired location.

Now navigate into the folder:

bash
Copy code
cd C:\Users\91846\Desktop\Predicting Market
✅ Step 4: Install Required Libraries
Install all dependencies using:

bash
Copy code
pip install -r requirements.txt
If any package fails individually, install manually like:

bash
Copy code
pip install requests numpy pandas matplotlib scikit-learn
✅ Step 5: Run the Application
Run this in your terminal:

bash
Copy code
python fina.py
The GUI window will launch.

🖼️ How to Use the GUI
Once the app opens, you'll see several buttons:

🔁 Load Live Dataset – Fetches and displays current prices in the text area.

📈 Live Prices Graph – Displays a line plot of BTC, DOGE, and LTC prices.

🔮 Predict Next 10 Days – Uses dummy historical data and Linear Regression to forecast prices.

📊 Train & Evaluate Model – Shows model performance metrics and a plot of predicted vs actual prices.
