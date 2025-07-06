# Flight Fare Prediction ✈️

This project predicts flight ticket prices using various flight-related features such as airline, source/destination cities, duration, number of stops, class, etc. It uses machine learning techniques for regression and model selection.

## 📌 Project Author

**Nayeem**  
GitHub: [Nayeem114477](https://github.com/Nayeem114477)  
Project Repo: [flight-fare-prediction](https://github.com/Nayeem114477/flight-fare-prediction)

---

## 📁 Dataset

The dataset used in this project can be downloaded from the following Google Drive link:

🔗 [Download Dataset](https://drive.google.com/file/d/1gX6ZJTkrVvUfXhGo-cMI5XO6cgdAYd0d/view?usp=drive_link)

Place the downloaded file in the `Notebook_Experiments/Data/` directory and rename it to `data.csv`.

---

## ⚙️ Tools & Technologies Used

- **Frontend**: Streamlit (for interactive prediction app)
- **Backend**: Python
- **Machine Learning**: scikit-learn, pandas, NumPy
- **Experiment Tracking**: MLflow
- **Version Control**: Git & GitHub
- **Environment Management**: Python `venv`
- **IDE**: VSCode / Jupyter Notebook

---

## 🚀 Features

- End-to-end ML pipeline: ingestion → transformation → model selection
- Multiple regression models with evaluation metrics
- MLflow-based experiment logging and comparison
- Streamlit frontend for real-time flight fare prediction

---

## 🛠️ How to Run

```bash
# 1 Clone the repository
git clone https://github.com/Nayeem114477/flight-fare-prediction.git
cd flight-fare-prediction

# 2 Create virtual environment (Python venv)
python -m venv myenv
myenv\Scripts\activate      # Windows
# source myenv/bin/activate   # macOS/Linux

# 3 Install dependencies
pip install -r requirements.txt

# 4 Set the Python path (Windows CMD)
set PYTHONPATH=.

# 5 Run training pipeline
python src/FlightPricePrediction/pipeline/training_pipeline.py

# 6 Run the prediction app
python app.py

# 7 (Optional) Launch Streamlit frontend
streamlit run app.py
```

---

## 📊 Example Models & R² Scores

- Linear Regression: ~0.90  
- Decision Tree: ~0.96  
- Random Forest: **~0.98** ✅ (Best)

---

## 📂 Project Structure

```
Flight-Fare-Prediction/
│
├── Notebook_Experiments/
├── src/
│   └── FlightPricePrediction/
│       ├── components/
│       ├── pipeline/
│       ├── utils/
│       └── exception.py
├── artifacts/
├── app.py  ← Streamlit frontend
└── README.md
```

---

## 📬 Contact

Feel free to reach out via [GitHub Issues](https://github.com/Nayeem114477/flight-fare-prediction/issues) or Linked in: (https://www.linkedin.com/in/mohammad-nayeem-1156a31b9/) if you have questions or suggestions.
