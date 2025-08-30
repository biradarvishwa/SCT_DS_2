# Titanic Dataset - Data Cleaning & Exploratory Data Analysis (EDA)

This project performs **data cleaning** and **exploratory data analysis (EDA)** on the Titanic dataset from [Kaggle](https://www.kaggle.com/competitions/titanic/data).  
The aim is to clean the dataset, handle missing values, and explore patterns and relationships in the data.

---

##  Files

| File Name                | Description                                   |
|-------------------------|------------------------------------------------|
| train.csv               | Training dataset with survival labels.         |
| test.csv                | Test dataset without survival labels.          |
| gender_submission.csv   | Sample submission file from Kaggle.            |
| titanic_eda.ipynb       | Jupyter Notebook with the analysis code.       |
| train_cleaned.csv       | Cleaned training dataset.                      |
| test_cleaned.csv        | Cleaned test dataset.                          |

---

##  Key Steps

1. **Data Loading**  
   - Load `train.csv` and `test.csv` datasets.  
   - Check dataset structure and features.

2. **Data Cleaning**  
   - Handle missing values in `Age`, `Embarked`, and `Fare`.  
   - Drop `Cabin` column due to many missing values.

3. **Exploratory Data Analysis (EDA)**  
   - Analyze survival rates based on gender, class, and embarkation port.  
   - Visualize correlations, distributions of age and fares.

4. **Data Export**  
   - Save cleaned datasets for future use.

---

##  Requirements

- Python 3.x  
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`  

Install dependencies:
```bash
pip install pandas numpy matplotlib seaborn

 How to Run

1.Clone this repository:

git clone https://github.com/yourusername/Titanic-EDA.git
cd Titanic-EDA
2.Run the Jupyter Notebook or Python script:
jupyter notebook titanic_eda.ipynb

3.View the analysis results and plots.
 Insights

Women had a much higher survival rate than men.

1st Class passengers were more likely to survive.

Ticket fares and class show a positive correlation with survival.
