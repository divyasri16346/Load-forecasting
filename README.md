# SmartLoad: Deep Learning for Power Load Forecasting & Proactive Load Shedding

> Forecast household electricity consumption using deep learning and automatically identify high-load periods for sustainable power grid management.

## 💡 Project Highlights

- Forecasts energy usage using 12-hour historical windows.
- Proactively sheds load when consumption crosses a threshold.
- Compares GRU, LSTM, BiLSTM, and N-BEATS-inspired models.
- Achieved **R² = 0.934**, **Precision = 89%**, **Recall = 70%** on peak load detection.
- Real-world sustainability impact: Avoid grid overloads, improve energy efficiency.

## 🧠 Models Used

- GRU
- LSTM
- BiLSTM
- Simplified N-BEATS (Feedforward)

## 📊 Results

| Model    | R² Score | MAE  | RMSE | Precision | Recall |
|----------|----------|------|------|-----------|--------|
| BiLSTM   | 0.934    | ...  | ...  | 89%       | 70%    |
| LSTM     | ...      | ...  | ...  | ...       | ...    |

## 🏗️ Setup Instructions

```bash
git clone https://github.com/yourusername/SmartLoad.git
cd SmartLoad
pip install -r requirements.txt
