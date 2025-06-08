# SmartLoad: Deep Learning for Power Load Forecasting & Proactive Load Shedding

> Forecast household electricity consumption using deep learning and automatically identify high-load periods for sustainable power grid management.

## 💡 Project Highlights

- Forecasts energy usage using 12-hour historical windows.
- Proactively sheds load when consumption crosses a threshold.
- Compares GRU, LSTM, BiLSTM, and N-BEATS-inspired models.
- Achieved **R² = 0.934**, **Precision = 89%**, **Recall = 70%** on peak load detection with Bi-LSTM.
- Real-world sustainability impact: Avoid grid overloads, improve energy efficiency.

## 🧠 Models Used

- GRU
- LSTM
- BiLSTM
- Simplified N-BEATS (Feedforward)

## 📊 Results

  Model       MAE      RMSE        R2     Precision    Recall
0      GRU  0.275415  0.511609  0.934060    0.863208  0.705656
1     LSTM  0.379214  0.549158  0.924025    0.851312  0.750643
2   BiLSTM  0.291597  0.510554  0.934332    0.890164  0.697943
3  N-BEATS  0.302547  0.524795  0.930617    0.880597  0.682519

## 🏗️ Setup Instructions

```bash
git clone https://github.com/yourusername/SmartLoad.git
cd SmartLoad
pip install -r requirements.txt
