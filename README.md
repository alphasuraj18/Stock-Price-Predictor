# 📈 Stock-Price-Predictor

A machine learning-based web application that predicts future stock prices using historical market data and compares multiple machine learning and deep learning models. This project leverages **Python, Streamlit, Pandas, NumPy, Matplotlib, Scikit-learn, TensorFlow, and Keras** to analyze stock trends and forecast future prices.

---

## 🚀 Features

- 📊 Real-time Stock Market Data Fetching
- 📈 Historical Price Visualization
- 🤖 Stock Price Prediction using 7 Models
- 📉 Moving Average Analysis (MA20, MA50, MA100, MA200)
- 🔍 Interactive Charts with Trend Analysis
- 🌐 Simple and User-Friendly Web Interface
- ⚡ Fast Predictions with Trained Models
- 📊 Model Performance Comparison
- 🧠 Deep Learning based Time-Series Forecasting

---

## 🛠️ Tech Stack

### Frontend
- Streamlit

### Backend
- Python

### Libraries Used
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Plotly  
- Scikit-learn  
- TensorFlow  
- Keras  
- yFinance  

---

## 📂 Project Structure

```bash
Stock-Price-Predictor/
│── app.py                               # Main Streamlit App
│── Comparative Analysis.ipynb          # Model Training Notebook
│── Stock Predictions Model.keras       # Saved Deep Learning Model
│── requirements.txt                    # Dependencies
│── README.md                           # Documentation
│── dataset/                            # Stock Dataset Files

```
---

## 🎯 Project Objective

The main goal of this project was to predict stock closing prices using past market data and compare different machine learning and deep learning models to identify which one performs best.

Instead of relying on only one algorithm, this project tests 7 different models to understand how traditional and advanced AI models behave on stock market data.

📊 Dataset Used

Historical NIFTY50 stock market data (2020 to 2024) was used for training and testing.

Dataset Features:
Open Price
High Price
Low Price
Close Price (Target Variable)

The Close Price is the value predicted by the models.

## Models Used in This Project
🔹 Classical Machine Learning Models (2)

1️⃣ Linear Regression
Used to find relationships between stock prices.
Fast and simple model
Good baseline model
Strong performance on structured data

2️⃣ Random Forest Regressor
Uses multiple decision trees for prediction.
Handles non-linear relationships
Reduces overfitting
Good for tabular data
🔹 Deep Learning Models (5)

3️⃣ Simple RNN

Learns patterns from previous stock prices.

4️⃣ LSTM (Long Short-Term Memory)
Special neural network designed for time-series data.
Remembers long-term trends
Highly effective for stock prediction

5️⃣ CNN (Convolutional Neural Network)
Used to detect short-term local patterns in stock movement.

6️⃣ GRU (Gated Recurrent Unit)
A faster and lighter version of LSTM.

7️⃣ Attention-Based LSTM
Advanced LSTM model that focuses on important previous data points for better prediction.

## ⚙️ Methodology

1️⃣ Data Preprocessing
Cleaned dataset
Removed missing values
Converted columns into usable format
Selected important features

2️⃣ Data Splitting

Dataset divided into:

80% Training Data
20% Testing Data

Training data was used to train the models and testing data was used for evaluation.


3️⃣ Feature Scaling

Used MinMaxScaler to normalize data between 0 and 1.

Benefits:

Faster model training
Better neural network performance

4️⃣ Sequence Creation (Deep Learning Models)

Previous stock prices were used to predict future price.

Example:

Last 10 Days Prices → Predict Next Day Closing Price

5️⃣ Model Training

All 7 models were trained and tested on the same dataset for fair comparison.

## 📈 Evaluation Metrics Used

To compare model performance:

MAE (Mean Absolute Error)
RMSE (Root Mean Squared Error)
R² Score
Direction Accuracy (Up / Down Prediction)

## 🏆 Final Results
Best Classical Model:

✅ Linear Regression

Best Deep Learning Models:

✅ Attention-LSTM
✅ CNN
✅ LSTM

Deep learning models performed better because they capture time-series dependencies more effectively.

## 📊 Visualizations Included
Closing Price vs Time
Moving Average (20 Days)
Moving Average (50 Days)
Moving Average (100 Days)
Moving Average (200 Days)
Actual vs Predicted Prices
Trend Analysis Graphs

## 💻 Installation & Setup
Clone Repository
git clone https://github.com/alphasuraj18/Stock-Price-Predictor.git
cd Stock-Price-Predictor
Install Dependencies
pip install -r requirements.txt
Run Application
streamlit run app.py

## 🌐 Usage
Enter Stock Symbol (Example: AAPL, TSLA, GOOG, RELIANCE.NS)
Select Date Range
View Historical Stock Charts
Compare Trends
Predict Future Closing Prices

## 📚 What I Learned
Machine Learning Model Comparison
Time Series Forecasting
Deep Learning for Finance
Data Preprocessing
Streamlit Web Deployment
Performance Evaluation Metrics

## 🔮 Future Improvements
Live Market Prediction
Buy/Sell Recommendation System
News Sentiment Analysis
Candlestick Charts
Portfolio Management Dashboard
Multi-stock Comparison

## ⚠️ Disclaimer

This project is for educational purposes only. Stock market investments involve risk. Predictions are not guaranteed.

## 🤝 Contributing

Pull requests are welcome. For major changes, open an issue first to discuss proposed changes.

## 📜 License

This project is open-source and available under the MIT License.

## 👨‍💻 Author
Suraj Kumar
🔗 GitHub: https://github.com/alphasuraj18

## ⭐ Support
If you found this project useful, give it a star ⭐ on GitHub.
