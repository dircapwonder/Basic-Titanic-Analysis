# 🚢 Titanic Dataset – Exploratory Data Analysis

A beginner-friendly exploratory data analysis (EDA) of the classic Titanic passenger dataset, built with **Python, Pandas, NumPy, Matplotlib and Seaborn**. The goal is to understand the data and see which factors were linked to survival — no machine learning models involved.

## 📁 Repository Structure

```
├── assignment.ipynb   # Jupyter Notebook with the full analysis
├── titanic.csv        # Titanic passenger dataset (891 rows, 12 columns)
└── README.md
```

## 📊 Dataset

The dataset contains 891 passengers and the following columns:

| Column | Description |
|---|---|
| `PassengerId` | Unique passenger ID |
| `Survived` | Survival (0 = No, 1 = Yes) |
| `Pclass` | Passenger class (1 = First, 2 = Second, 3 = Third) |
| `Name` | Passenger name |
| `Sex` | Gender |
| `Age` | Age in years |
| `SibSp` | Number of siblings / spouses aboard |
| `Parch` | Number of parents / children aboard |
| `Ticket` | Ticket number |
| `Fare` | Ticket fare |
| `Cabin` | Cabin number |
| `Embarked` | Port of embarkation (C, Q, S) |

## 🎯 What the Notebook Covers

1. Load the dataset with Pandas
2. Inspect shape, columns and basic information
3. Check for missing values and handle them
4. Count how many passengers survived / did not survive
5. Analyze survival by gender
6. Analyze survival by passenger class
7. Find the average age and average fare
8. Create simple visualizations to support the findings

**Bonus challenges**

- Survival rates across age groups
- Fare distribution for survivors vs. non-survivors
- Additional insight: survival rate by gender

## 🔍 Key Findings

- **Overall survival:** 342 of 891 passengers survived (about 38%); 549 did not.
- **Gender:** Women survived at roughly **74%**, men at only about **19%**.
- **Passenger class:** Survival dropped with class — about **63%** (1st), **47%** (2nd), **24%** (3rd).
- **Age groups:** Children had the highest survival rate (about 58%), while elderly passengers had the lowest (about 23%).
- **Averages:** Mean age ≈ **29.7** years, mean fare ≈ **32.2**.
- **Missing values:** `Age` (177), `Cabin` (687) and `Embarked` (2) contained missing data.

## 🛠️ Technologies Used

- Python 3
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/dircapwonder/Basic-Titanic-Analysis.git
   cd Basic-Titanic-Analysis
   ```
2. Install the dependencies:
   ```bash
   pip install numpy pandas matplotlib seaborn jupyter
   ```
3. Launch Jupyter and open the notebook:
   ```bash
   jupyter notebook assignment.ipynb
   ```

> Make sure `titanic.csv` is in the same folder as the notebook.

## 📌 Notes

- The analysis is intentionally simple and focuses on understanding the data rather than optimization.
- No machine learning models are trained.

## 📄 License

This project is for educational purposes.
