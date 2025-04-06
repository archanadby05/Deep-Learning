## GRU-Based Stock Price Forecasting with ASIANPAINT Dataset

This project implements a deep learning model using Gated Recurrent Units (GRUs) to forecast stock prices based on historical time series data. The model is trained and evaluated using the ASIANPAINT stock dataset.

---

### Project Objective

To forecast future stock prices using GRU-based recurrent neural networks, demonstrating the effectiveness of deep learning for sequential data modeling in the financial domain.

---

### Overview

- **Model**: GRU (Gated Recurrent Unit)
- **Domain**: Stock Price Forecasting
- **Dataset**: ASIANPAINT stock data (NSE)
- **Approach**:
  - Data cleaning and preprocessing
  - Feature engineering using moving averages
  - Train-test split and scaling
  - GRU model training and evaluation
  - Visualization of predictions vs actual values

---

### Dataset Details

- **File**: `ASIANPAINT.csv`
- **Fields used**: `Date`, `Open`, `High`, `Low`, `Close`, `VWAP`, `Volume`
- **Preprocessing**:
  - Handled missing values
  - Extracted and transformed relevant features
  - Applied scaling and smoothing techniques

---

### Technologies Used

- Python
- NumPy & Pandas
- Scikit-learn
- TensorFlow / Keras
- Matplotlib

---

### Results

The model output includes a visual comparison of predicted vs actual closing prices over the test period, demonstrating the model's ability to capture stock price trends on unseen data.

<p align="center">
  <img src="https://github.com/user-attachments/assets/2b17e095-3738-43ae-b65a-48bfa8819c9e" alt="Predicted vs Actual Prices" width="600"/>
</p>


---

### Getting Started

1. Clone the repository or upload the notebook to Colab
2. Ensure required libraries are installed
3. Open the notebook:

```bash
jupyter notebook GRU_Based_Stock_Price_Forecasting.ipynb
