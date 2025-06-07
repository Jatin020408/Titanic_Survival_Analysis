# Titanic Survival Analysis

This project uses the famous Titanic dataset to perform exploratory data analysis (EDA) and understand the key factors that influenced survival. It visualizes patterns in survival rates based on passenger class, sex, number of siblings/spouses onboard, and parents/children aboard.

---

## Dataset

**Source**: [Titanic - Machine Learning from Disaster (Kaggle)](https://www.kaggle.com/competitions/titanic/data)  
**Format**: CSV  
**Filename**: `titanic.csv`

---

## Tools and Libraries

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Jupyter Notebook
- `jupyterthemes` (for dark theme styling)

---

## Exploratory Data Analysis

The analysis focuses on visualizing how different factors affect survival. Here's what's done:

- **Survival Distribution**: Count of survivors vs. non-survivors.
- **Pclass (Passenger Class)**:
  - Survival rates by passenger class.
- **SibSp (Siblings/Spouses Aboard)**:
  - Influence of having siblings/spouses onboard on survival.
- **Parch (Parents/Children Aboard)**:
  - How having family affected survival likelihood.
- **Sex**:
  - Gender-based survival probabilities (spoiler: women had a higher chance!).

Each factor is visualized with dual bar charts (overall and survival-split) for easy comparison.

---

## Sample Visualizations

Here's a preview of some plots generated:

- Survival by Passenger Class
- Survival by Number of Siblings/Spouses
- Survival by Gender
- Survival by Number of Parents/Children

> *Note: Make sure to run the notebook to generate and view all these visualizations!*

---

## How to Run

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/titanic-survival-analysis.git
cd titanic-survival-analysis

# 2. Install required libraries (use a virtual environment if needed)
pip install -r requirements.txt

# 3. Launch the Jupyter Notebook
jupyter notebook main.ipynb
```

Ensure you have the `titanic.csv` file in the same directory as `main.ipynb`.

---

## To-Do

- Impute missing values (Age, Cabin, Embarked)
- Feature engineering (e.g., family size, title extraction from name)
- Train a machine learning model for prediction
- Export as web dashboard (Streamlit/Flask)

---
