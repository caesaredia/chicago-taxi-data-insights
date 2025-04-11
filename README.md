# Chicago Taxi Trip Analysis and Hypothesis Testing

This project performs exploratory data analysis (EDA) and hypothesis testing using datasets related to taxi trips in Chicago. The main focus includes identifying demand hotspots, understanding taxi company performance, and evaluating the impact of rainy weather on trip durations from downtown Chicago (Loop) to O’Hare International Airport.

---

## 📊 Project Objectives

### 1. Exploratory Data Analysis
- Analyze taxi companies based on trip volumes on November 15–16, 2017.
- Identify the top 10 drop-off areas in Chicago by average number of trips during November 2017.
- Visualize distribution of trips per taxi company and per drop-off area.

### 2. Hypothesis Testing
- **Null Hypothesis (H₀):** The average trip duration from the Loop to O’Hare International Airport does not change on rainy Saturdays.
- **Alternative Hypothesis (H₁):** The average trip duration from the Loop to O’Hare International Airport changes on rainy Saturdays.
- Method: Independent t-test with a significance level (α) of 0.05.

---

## 📁 Datasets

All datasets used in this project are stored in the `data/` directory:
- `data/chicago_taxi_data_01.csv`: Taxi company data for Nov 15–16, 2017.
- `data/chicago_taxi_data_02.csv`: Average drop-off volume per area.
- `data/chicago_taxi_data_03.csv`: Trip records from Loop to O’Hare with weather data.

---

## 📈 Key Findings

- **Flash Cab** had the highest number of trips on Nov 15–16, indicating strong demand or superior service.
- **Loop**, **River North**, and **Streeterville** were the top destinations, reflecting their high popularity.
- **Hypothesis testing** revealed a statistically significant increase in trip duration on rainy Saturdays, supporting the alternative hypothesis.

---

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- SciPy (for statistical testing)
- Jupyter Notebook

---

## Author
Nabilla Hafsah Caesaredia

---

## 📌 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/chicago-taxi-analysis.git
