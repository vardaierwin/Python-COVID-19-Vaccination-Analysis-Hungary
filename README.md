🦠 COVID-19 Vaccination Analysis – Hungary 🇭🇺
📘 Project Overview

This project analyzes COVID-19 vaccination trends in Hungary using Python.
The goal is to explore vaccination progress, identify peak vaccination periods, and examine the relationship between new cases, vaccinations, and booster rollout.
The project demonstrates skills in data cleaning, transformation, aggregation, and visualization with Pandas, NumPy, and Matplotlib.

🎯 Objectives / Key Questions

How did vaccination rates evolve over time in Hungary?

When did the highest daily vaccination peaks occur?

What was the relationship between new COVID cases and vaccination activity?

How did booster rollout progress globally compared to Hungary?

🧩 Data Source

Dataset: Our World in Data – COVID-19 Dataset

File used: compact.csv (subset focusing on Hungary)
Main fields:

date – record date

country – country name

new_vaccinations – daily new vaccinations

total_vaccinations – cumulative vaccinations

people_vaccinated_per_hundred, people_fully_vaccinated_per_hundred – per-capita indicators

total_boosters_per_hundred, new_cases – booster and infection metrics

⚙️ Technologies Used

Python 3

Pandas – data manipulation and aggregation

NumPy – numeric processing

Matplotlib – data visualization

🔄 Process Summary

Data Import & Inspection: Loaded compact.csv and explored structure with Pandas.

Filtering: Selected Hungarian data (country == "Hungary").

Cleaning: Handled missing values, normalized date formats, and removed duplicates.

Aggregation: Computed total and average vaccinations by date and month.

Analysis: Identified peak vaccination days, first 5M milestone, and compared with case counts.

Visualization:

Daily vaccination bars with max-highlight.

Vaccination progress (% per hundred).

Booster rate evolution globally.

Dual-axis chart for new cases vs vaccinations.

Monthly average vaccination rates.

📊 Key Insights

Peak vaccination day: Clearly visible in red on bar chart — corresponding to Hungary’s highest recorded daily vaccination rate.

Milestone: 5M total vaccinations reached within the first major rollout wave.

Strong negative correlation observed between new vaccinations and new cases (as vaccines increased, cases decreased).

Global booster uptake followed a slower but steady trend.

Monthly averages revealed significant seasonal fluctuations in vaccination intensity.

📈 Sample Visualizations

New Vaccinations per Day in Hungary

Total Progress of Vaccination (% of population)

Global Booster Evolution

New Cases vs New Vaccinations (dual axis)

Monthly Average Vaccination Trends
