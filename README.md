# World-energy-consumption
# Energy Consumption Forecasting Using RNN and LSTM

## 📌 Project Overview
This project predicts a country's future energy consumption using historical energy consumption data. It uses deep learning models such as Simple Recurrent Neural Network (RNN) and Long Short-Term Memory (LSTM) to forecast energy consumption for the next year.

## 🎯 Objectives
- Analyze historical energy consumption data.
- Handle missing values and normalize numerical features.
- Create sequences using the previous five years of data.
- Build and train Simple RNN and LSTM models.
- Predict future energy consumption and compare model performance.

## 📊 Dataset
- **Dataset Name:** World Energy Consumption
- **Source:** Kaggle
- **Country:** Selected country with sufficient yearly records
- **Target Variable:** Energy Consumption

## 🛠️ Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- TensorFlow / Keras

## 🧠 Models Used
1. **Simple RNN:** Learns patterns from sequential energy consumption data.
2. **LSTM:** Captures long-term dependencies in historical time-series data.

## ⚙️ Methodology
1. Load the dataset.
2. Select a country and relevant numerical features.
3. Handle missing values.
4. Normalize the selected features.
5. Sort the records by year.
6. Create input sequences using the previous five years.
7. Train the Simple RNN and LSTM models.
8. Predict energy consumption for the next year.
9. Evaluate and compare model performance.

## ▶️ How to Run
1. Open the Google Colab notebook.
2. Upload or load the World Energy Consumption dataset.
3. Run the notebook cells in order.
4. Train the RNN and LSTM models.
5. View the predictions, evaluation metrics, and comparison graphs.

## 📈 Results
The performance of the Simple RNN and LSTM models is evaluated using appropriate regression metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).

*Add the actual results and graphs after running the notebook.*

## 📁 Project Structure
```text
Energy-Consumption-Forecasting/
├── energy_forecasting.ipynb
├── README.md
└── dataset.csv (optional)
```

## 👩‍💻 Author
Darsani Priya RJ

## 📜 License
This project is intended for educational and academic purposes.
