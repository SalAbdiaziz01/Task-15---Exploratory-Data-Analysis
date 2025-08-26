# Titanic Exploratory Data Analysis (EDA)

**Goal:** Explore the Titanic dataset to understand passenger demographics, survival factors, and relationships between key features.

---

## 📊 Data
- **Source:** [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)
- **Files:**
  - `titanic.csv` — main dataset (891 passengers, 12 features)
  - `titanic_eda.ipynb` — Jupyter notebook with analysis
  - `titanic.html` — exported notebook view

---

## 🔎 Method
- Data cleaning (null values, type conversion)
- Exploratory analysis with pandas + matplotlib
- Feature breakdowns: gender, age groups, passenger class, embarkation port
- Visualisations: survival rates by multiple categories

---

## ✅ Key Findings
- Women and children had significantly higher survival rates.
- Survival was strongly correlated with passenger class (wealth).
- Passengers who embarked at Cherbourg had higher survival chances.

---

## ▶️ How to Run
Clone this repo and install dependencies:

```bash
git clone https://github.com/SalAbdiaziz01/Exploratory-Data-Analysis-Titanic.git
cd Exploratory-Data-Analysis-Titanic
python -m venv .venv && source .venv/bin/activate   # or .venv\Scripts\activate on Windows
pip install -r requirements.txt
jupyter notebook titanic_eda.ipynb
