# Stock-Price-Predictor

A machine learning-based web application that predicts future stock prices using historical market data and deep learning techniques. This project leverages **Python, Streamlit, Pandas, NumPy, Matplotlib, Scikit-learn, and LSTM Neural Networks** to analyze stock trends and forecast future prices.

---

## 🚀 Features

- 📊 Real-time Stock Market Data Fetching
- 📈 Historical Price Visualization
- 🤖 Stock Price Prediction using LSTM Model
- 📉 Moving Average Analysis (MA50, MA100, MA200)
- 🔍 Interactive Charts with Trend Analysis
- 🌐 Simple and User-Friendly Web Interface
- ⚡ Fast Predictions with Trained Model

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
- Plotly  
- Scikit-learn  
- TensorFlow / Keras  
- yFinance  

---

## 📂 Project Structure

```bash
Stock-Price-Predictor/
│── app.py                 # Main Streamlit App
│── Stock Predictions Model.keras   # Trained LSTM Model
│── requirements.txt       # Dependencies
│── README.md              # Project Documentation

## 🎯 Project Objective

The main goal of this project was to predict stock closing prices using past market data and compare different machine learning and deep learning models to see which one performs best.

Instead of using only one algorithm, I tested 7 different models to understand how traditional models and advanced neural networks behave on stock market data.

📊 Dataset Used

I used historical NIFTY50 stock market data (2020 to 2024).

The dataset included daily values such as:

Open Price
High Price
Low Price
Close Price

The Close Price was the target value that I wanted to predict.

## Models Used in This Project
🔹 Classical Machine Learning Models (2)
1. Linear Regression

Used to find the relationship between stock prices.

Fast and simple model
Good for baseline comparison
2. Random Forest Regressor

Used multiple decision trees for prediction.

Handles non-linear data
More powerful than simple regression
🔹 Deep Learning Models (5)
3. Simple RNN

Learns patterns from previous stock prices.

4. LSTM

Special neural network made for time-series data.

Remembers long-term trends
Very useful in stock prediction
5. CNN

Used to detect short-term patterns in stock movement.

6. GRU

A lighter and faster version of LSTM.

7. Attention-Based LSTM

Advanced version of LSTM that focuses more on important past data.

⚙️ Methodology
Step 1: Data Preprocessing

I cleaned the dataset, handled missing values, converted data into proper format, and selected useful columns.

Step 2: Data Splitting

The data was divided into:

80% Training Data
20% Testing Data

Training data was used to teach the models, and testing data was used to check performance.

Step 3: Feature Scaling

I used MinMaxScaler to convert values between 0 and 1.

This helps models train faster and perform better.

Step 4: Sequence Creation (For Deep Learning)

For deep learning models, I used previous few days’ prices to predict the next day price.

Example:

Last 10 days prices → Predict next day closing price

Step 5: Model Training

All models were trained and tested using the same dataset.

Then their results were compared.

📈 Evaluation Metrics Used

To compare performance, I used:

MAE (Mean Absolute Error)
RMSE (Root Mean Square Error)
R² Score
Direction Accuracy (Up/Down movement)

⚠️ Disclaimer

This project is for educational purposes only. Stock market investments involve risk. Predictions are not guaranteed.

🤝 Contributing

Pull requests are welcome. For major changes, open an issue first to discuss improvements.

📜 License

This project is open-source and available under the MIT License.

👨‍💻 Author

Suraj Kumar
🔗 GitHub: https://github.com/alphasuraj18
