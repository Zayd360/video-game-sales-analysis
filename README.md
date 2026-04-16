# 🎮 Video Game Sales Analysis

An end-to-end data analysis project exploring video game sales patterns across platforms, genres, publishers, and regions using statistical methods and regression models.

---

## 📌 Overview

This project analyzes a comprehensive video game sales dataset to uncover how factors such as platform, genre, publisher, and region influence global sales.

The analysis includes:

- 📊 Exploratory Data Analysis (EDA)
- 📈 Linear Regression (statistical model)
- 🤖 KNN Regression (comparison model)

---

## 📂 Dataset

- **Source:** [Zenodo – Video Game Sales Dataset](https://zenodo.org/records/5898311)
- **Type:** Public research dataset

> Note: Government datasets were explored but did not provide sufficient detailed video game sales data. A research dataset from Zenodo was used instead.

### 📊 Dataset Features

| Column | Description |
|---|---|
| `Name` | Game title |
| `Platform` | Gaming platform (DS, PS2, Wii, etc.) |
| `Year` | Year of release |
| `Genre` | Game genre |
| `Publisher` | Game publisher |
| `NA_Sales` | North America sales (millions) |
| `EU_Sales` | Europe sales (millions) |
| `JP_Sales` | Japan sales (millions) |
| `Other_Sales` | Rest of world sales (millions) |
| `Global_Sales` | Total worldwide sales (millions) |

---

## 🔍 Exploratory Data Analysis (EDA)

The following analyses and visualizations were produced:

| # | Visualization |
|---|---|
| 1 | 🏆 Top 10 Best-Selling Games by Global Sales |
| 2 | 🖥️ Top 5 Platforms by Total Sales |
| 3 | 🎭 Popularity of Game Genres by Global Sales |
| 4 | 📊 Number of Games by Genre |
| 5 | 📅 Global Video Game Sales Trend Over Years |
| 6 | 📦 Platform-wise Sales Distribution |
| 7 | 🏢 Top 10 Publishers by Global Sales |
| 8 | 🏅 Top Publisher by Region |
| 9 | 🔥 Correlation Between Regional and Global Sales |
| 10 | 📈 Sales Trends by Genre Over Time |
| 11 | 🏭 Publisher Sales Trends Over Time |
| 12 | 🔢 Top Publishers with Most Games Released |

---

## 📈 Regression Analysis

Two regression models were used to analyze the relationship between regional sales and global sales:

### Linear Regression
- **Features:** `NA_Sales`, `EU_Sales`, `JP_Sales`
- **Target:** `Global_Sales`

### KNN Regression
- **Features:** `NA_Sales`, `EU_Sales`, `JP_Sales`
- **Target:** `Global_Sales`
- Used for performance comparison against linear regression

**Model Performance Metrics:** R² Score and RMSE were compared across both models.

---

## 📊 Sample Visualizations

![Top 10 Games by Global Sales](images/Top%2010%20Games%20by%20Global%20Sales.png)
![Top 5 Platforms by Total Sales](images/Top%205%20Platforms%20by%20Total%20Sales.png)
![Correlation Between Regional and Global Sales](images/Correlation%20Between%20Regional%20and%20Global%20Sales.png)
![Popularity of Game Genres by Global Sales](images/Popularity%20of%20Game%20Genres%20by%20Global%20Sales.png)
![Global Video Game Sales Trend Over Years](images/Global%20Video%20Game%20Sales%20Trend%20Over%20Years.png)

---

## 📊 Key Insights

- Regional sales (NA, EU, JP) are strong predictors of global sales
- Strong positive correlation exists between NA, EU, and global sales
- Genre significantly affects game sales
- A small number of top publishers dominate global sales figures
- Sales peaked mid-2000s and show a declining trend in later years

---

## 🛠️ Technologies Used

| Tool | Purpose |
|---|---|
| Python | Core language |
| Pandas | Data loading & manipulation |
| Matplotlib | Custom visualizations |
| Seaborn | Statistical plots |
| Scikit-learn | Linear & KNN regression |
| SciPy | Hypothesis testing (T-Test, ANOVA) |
| Jupyter Notebook | Interactive analysis environment |

---

## 🚀 How to Run

```bash
git clone https://github.com/Zayd360/video-game-sales-analysis.git
cd video-game-sales-analysis
pip install -r requirements.txt
jupyter notebook
```

Then open `vgsales_analysis.ipynb` and run all cells.

---

## 📁 Project Structure

```
video-game-sales-analysis/
├── vgsales_analysis.ipynb   # Main analysis notebook
├── vgsales.csv              # Dataset
├── images/                  # Generated visualizations
└── README.md
```

---

## 📌 Project Highlights

- Clean, structured end-to-end analysis pipeline
- Statistical methods (T-Test, ANOVA, Regression) — no heavy ML
- Real-world public dataset from Zenodo
- Rich visualizations with clear insights

---

## 👨‍💻 Author

**Zayd**

---

## ⭐ Found this useful?

Give this repo a ⭐ on GitHub!
