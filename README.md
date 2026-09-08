# Titanic Exploratory Data Analysis (EDA)

## Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the famous Titanic dataset to understand the factors that influenced passenger survival.

The analysis explores passenger demographics, ticket classes, fares, age, gender, family size, and port of embarkation using Python and data visualization techniques.

---

## Objective

The main objectives of this project are:

* Understand the Titanic dataset.
* Perform data cleaning and preprocessing.
* Handle missing values.
* Analyze passenger survival patterns.
* Explore relationships between survival and different passenger characteristics.
* Create meaningful visualizations.
* Extract important insights from the data.

---

## Dataset

The dataset used in this project is the **Titanic dataset**.

### Dataset Details

* **Rows:** 891
* **Columns:** 12
* **Target Variable:** `Survived`

### Important Columns

| Column      | Description                       |
| ----------- | --------------------------------- |
| PassengerId | Unique passenger ID               |
| Survived    | Survival status (0 = No, 1 = Yes) |
| Pclass      | Passenger class                   |
| Name        | Passenger name                    |
| Sex         | Passenger gender                  |
| Age         | Passenger age                     |
| SibSp       | Number of siblings/spouses aboard |
| Parch       | Number of parents/children aboard |
| Ticket      | Ticket number                     |
| Fare        | Passenger fare                    |
| Cabin       | Cabin number                      |
| Embarked    | Port of embarkation               |

---

## Technologies Used

* **Python**
* **Jupyter Notebook**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**

---

## EDA Process

The project follows these major steps:

### 1. Data Loading

The Titanic dataset was loaded into a Pandas DataFrame.

### 2. Data Understanding

The dataset was examined using:

* `head()`
* `tail()`
* `shape`
* `info()`
* `describe()`
* Unique value analysis

### 3. Data Cleaning

The dataset was checked for:

* Missing values
* Duplicate records
* Incorrect or inconsistent data

Missing values were handled using appropriate techniques.

For example, missing values in the `Age` column were replaced using the median age.

### 4. Statistical Analysis

Descriptive statistics were used to understand:

* Age distribution
* Fare distribution
* Passenger class
* Family-related variables
* Survival distribution

### 5. Data Visualization

Different visualizations were created to identify patterns and relationships, including:

* Count plots
* Bar charts
* Histograms
* Box plots
* Pie charts
* Correlation analysis

---

## Key Analysis Areas

The analysis focuses on:

### Overall Survival

The overall survival rate of Titanic passengers was analyzed to understand the proportion of passengers who survived and those who did not.

### Survival by Gender

Survival was compared between male and female passengers.

### Survival by Passenger Class

Passenger classes were analyzed to determine whether class was associated with survival.

### Age Analysis

Passenger age distribution was explored, including the relationship between age and survival.

### Fare Analysis

Passenger fares were analyzed to identify differences across passenger groups and classes.

### Family Size

The relationship between family size and passenger survival was explored using `SibSp` and `Parch`.

### Port of Embarkation

Passenger survival patterns were also examined according to their port of embarkation.

---

## Key Insights

The analysis highlights several important patterns:

* Passenger survival was strongly associated with **gender**.
* **Female passengers had a considerably higher survival rate** than male passengers.
* Passenger **class had a significant relationship with survival**.
* Passengers from higher classes generally had better survival outcomes.
* Age showed differences across surviving and non-surviving passengers.
* Fare values varied significantly across passenger classes.
* Family size showed a relationship with survival patterns.

---

## Visualizations

The notebook contains multiple visualizations that help explain the Titanic survival patterns.

Some of the major visual analyses include:

* Survival Distribution
* Survival by Gender
* Survival by Passenger Class
* Age Distribution
* Fare Distribution
* Family Size Analysis
* Embarkation Analysis
* Correlation Heatmap

---

## Project Structure

```text
Titanic-EDA/
│
├── Titanic-EDA.ipynb
├── train.csv
├── Titanic-EDA-Report.pdf
└── README.md
```

---

## How to Run the Project

### Step 1: Clone the Repository

Clone this repository to your local system.

### Step 2: Install Required Libraries

Run:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Step 3: Open the Notebook

Open:

```text
Titanic-EDA.ipynb
```

using Jupyter Notebook or VS Code.

### Step 4: Run the Notebook

Run all cells from beginning to end to reproduce the analysis and visualizations.

---

## Project Deliverables

This project contains:

* **Jupyter Notebook:** `Titanic-EDA.ipynb`
* **PDF Report:** `Titanic-EDA-Report.pdf`
* **Dataset:** `train.csv`
* **Documentation:** `README.md`

---

## Conclusion

The Titanic dataset provides a useful example of how Exploratory Data Analysis can be used to discover meaningful patterns in real-world data.

Through data cleaning, statistical analysis, and visualization, this project demonstrates how passenger characteristics such as **gender, passenger class, age, fare, and family-related factors** were associated with survival outcomes.

This project demonstrates practical skills in **Python, Pandas, data cleaning, data visualization, statistical analysis, and exploratory data analysis**.

---

## Author

(Nitesh Prajapati)

### GitHub

(niteshprajapati07)

#....END...#
