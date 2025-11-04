# 🦠 COVID-19 Vaccination Analysis – Hungary

## 📘 Project Overview

This project analyzes COVID-19 vaccination trends in Hungary using Python.
The goal is to explore vaccination progress, identify peak vaccination periods, and examine the relationship between new cases, vaccinations, and booster rollout.
The project demonstrates skills in data cleaning, transformation, aggregation, and visualization with Pandas, NumPy, and Matplotlib.

## 🎯 Objectives / Key Questions

* How did vaccination rates evolve over time in Hungary?

* When did the highest daily vaccination peaks occur?

* What was the relationship between new COVID cases and vaccination activity?

* How did booster rollout progress globally compared to Hungary?

## 🧩 Data Source

Dataset: Our World in Data – COVID-19 Dataset

File used: `compact.csv` (subset focusing on Hungary, link: https://catalog.ourworldindata.org/garden/covid/latest/compact/compact.csv)

**Main fields**:

`date` – record date

`country` – country name

`new_vaccinations` – daily new vaccinations

`total_vaccinations` – cumulative vaccinations

`people_vaccinated_per_hundred`, `people_fully_vaccinated_per_hundred` – per-capita indicators

`total_boosters_per_hundred`, `new_cases` – booster and infection metrics

## ⚙️ Technologies Used

Python 3

`Pandas` – data manipulation and aggregation

`NumPy` – numeric processing

`Matplotlib` – data visualization

## 🔄 Process Summary

**Data Import & Inspection**: Loaded `compact.csv` and explored structure with `Pandas`.

**Filtering**: Selected Hungarian data (`country == "Hungary"`).

**Cleaning**: Handled missing values, normalized date formats, and removed duplicates.

**Aggregation**: Computed total and average vaccinations by date and month.

## Visualization:

Created multiple plots including daily vaccination bars with peak highlights, vaccination progress (% per hundred), booster rollout trends, dual-axis charts comparing new cases vs vaccinations, and monthly average vaccination rates.
