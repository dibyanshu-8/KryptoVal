# KRYPTOVAL - Cryptocurrency Price Prediction

KRYPTOVAL is a web application that predicts the price of various cryptocurrencies using a Long Short-Term Memory (LSTM) deep learning model. Real-time cryptocurrency data is sourced from the Yahoo Finance API (`yfinance`), and the model is deployed using the Flask web framework.

## 📖 Project Description

The primary goal of KRYPTOVAL is to provide a user-friendly platform for cryptocurrency price prediction. The project leverages the power of deep learning to analyze historical price data and forecast future price movements. The key components of the project are:

* **Data Acquisition:** Real-time cryptocurrency data is fetched using the `yfinance` library, which provides a convenient interface to Yahoo Finance's extensive financial data.
* **Predictive Modeling:** A Long Short-Term Memory (LSTM) neural network, a type of Recurrent Neural Network (RNN), is used to model the time-series data of cryptocurrency prices. LSTMs are particularly effective at learning long-term dependencies, which is crucial for financial forecasting.
* **Web Deployment:** The trained LSTM model is deployed using Flask, a lightweight Python web framework. This allows users to interact with the model through a simple and intuitive web interface.

## ✨ Features

* **Real-time Price Prediction:** Get up-to-date price predictions for a wide range of cryptocurrencies.
* **Interactive Web Interface:** A user-friendly interface to select a cryptocurrency and view its predicted price.
* **LSTM-based Model:** Utilizes a powerful deep learning model for accurate time-series forecasting.
* **Easy to Use:** Simply select a cryptocurrency and get the prediction without any complex setup.

## 🛠️ Technologies Used

* **Machine Learning/Deep Learning:**
    * Python
    * TensorFlow / Keras
    * Scikit-learn
    * NumPy
    * Pandas
* **Data Source:**
    * yfinance API (Yahoo Finance)
* **Web Framework:**
    * Flask

## ⚙️ Installation and Setup

To run this project locally, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/KRYPTOVAL.git](https://github.com/your-username/KRYPTOVAL.git)
    cd KRYPTOVAL
    ```

2.  **Create and activate a virtual environment:**
    ```bash
    python -m venv venv
    # On Windows
    venv\Scripts\activate
    # On macOS/Linux
    source venv/bin/activate
    ```

3.  **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Run the Flask application:**
    ```bash
    python app.py
    ```

5.  Open your web browser and navigate to `http://127.0.0.1:5000/`.





