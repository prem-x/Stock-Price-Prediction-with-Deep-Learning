# 📈 Stock Price Prediction with Deep Learning

This project demonstrates **stock price forecasting** using **Deep Learning models (RNN & LSTM)** on historical stock market data. The goal is to analyze temporal patterns in stock prices and predict future closing prices using neural networks.

<br>

## ❖ Project Overview

* Implemented **Recurrent Neural Network (RNN)** and **Long Short-Term Memory (LSTM)** models
* Used historical stock price data (AABA)
* Applied **time series preprocessing**, scaling, and sliding window techniques
* Compared **model performance** using MAE and validation loss
* Visualized **historical prices, actual test data, and future forecasts**

<br>

## ❖ Models Used

### ⬡ RNN (SimpleRNN)

* Lightweight architecture
* Smooth learning with minimal overfitting
* Final MAE ≈ **0.108**

### ⬡ LSTM

* Better temporal memory
* Improved training accuracy
* Slight overfitting after epoch 5
* Used for **recursive future forecasting**

<br>

## ❖ Dataset

* **File:** `AABA_2006-01-01_to_2018-01-01.csv`
* **Features Used:**

  * Date
  * Open
  * High
  * Low
  * Close
  * Volume

<br>

## ❖ Technologies & Tools

* Python 🐍
* NumPy, Pandas
* Matplotlib, Seaborn
* Scikit-learn
* TensorFlow / Keras
* Jupyter Notebook

<br>

## ❖ Workflow

1. Data loading & cleaning
2. Exploratory Data Analysis (EDA)
3. Feature scaling using MinMaxScaler
4. Sequence generation (sliding window)
5. Model building (RNN & LSTM)
6. Model training & validation
7. Forecasting & inverse scaling
8. Visualization of results

<br>

## ❖ Results

* RNN performed well with stable generalization
* LSTM captured temporal dependencies effectively
* Recursive LSTM forecasting generated **25 future price predictions**


<br>


## ❖ How to Run

```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow
```

Open the notebook:

```bash
jupyter notebook "Stock Price Prediction with Deep Learning.ipynb"
```

<br>

## ❖ Conclusion

This project highlights the effectiveness of deep learning models for financial time series forecasting and demonstrates practical implementation of RNN and LSTM architectures for stock price prediction.

<br>

## ❖ License

This project is for **educational purposes only**.
