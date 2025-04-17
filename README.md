# RNN-Applications-Website-Traffic-Forecasting-Next-Word-Prediction


---

## 🧰 Technologies Used

- Python
- TensorFlow / Keras
- NumPy, Pandas, Matplotlib
- Scikit-learn (for preprocessing)

---

## 📈 Time Series Forecasting (Website Traffic)

- Model: LSTM
- Input: Daily visitor counts, holidays, promotions
- Output: Next day's visitor prediction
- Evaluation: MSE, RMSE

---

## ✍️ Next Word Prediction (NLP)

- Model: RNN / LSTM
- Input: Sequences of words
- Output: Predicted next word from vocabulary
- Evaluation: Accuracy, Perplexity

---

## 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/yourusername/rnn-overview.git
cd rnn-overview

# Install dependencies
pip install -r requirements.txt

# Run time series model
python traffic_forecasting/lstm_traffic_model.py

# Run next word prediction model
python next_word_prediction/next_word_model.py
