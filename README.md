**🦠📊 COVID-19 Mortality Analysis (R Project)
📌🧾 Project Overview

This project analyzes COVID-19 mortality data to identify key demographic risk factors associated with death outcomes.
Using R and statistical analysis, the study explores how age, gender, time, and geographic location influence mortality rates.

The project was developed as part of a data analytics portfolio, focusing on data cleaning, hypothesis testing, and data visualization.

🎯📍 Objectives

🧹 Clean and preprocess raw COVID-19 patient data

📈 Calculate overall and subgroup mortality rates

🧪 Compare mortality by age and gender using statistical tests

📅 Visualize mortality trends over time

🌍 Identify high-risk age groups, genders, and countries

📊🗂 Dataset

Source: COVID-19 line-list dataset

Type: Patient-level epidemiological data

Key Variables:

age

gender

country

death (binary outcome)

reporting.date

⚠️ Missing age values were imputed using the mean age, and non-analytical metadata columns were removed.

🧹🧼 Data Cleaning Steps

🔁 Converted the death variable into a binary format (0 = alive, 1 = deceased)

🧮 Imputed missing age values using the mean

🔢 Rounded age values for grouping

🗑 Removed irrelevant metadata columns

📆 Converted reporting dates to proper date format

📈📉 Analysis Performed
👵📊 1. Age vs Mortality

Compared mean ages of deceased and surviving patients

Conducted a Welch Two-Sample t-test (99% confidence level)

🚻📊 2. Gender vs Mortality

Calculated death rates by gender

Performed a t-test to assess gender disparity

⏳📈 3. Time Series Analysis

Visualized daily COVID-19 deaths over time using line plots

👶➡️👴 4. Age Group Analysis

Categorized ages into:

0–20

21–40

41–60

61–80

81+

Identified the most vulnerable age groups

🌍📊 5. Geographical Analysis

Compared death counts across countries

Highlighted countries with higher mortality counts

🔄👫 6. Age & Gender Interaction

Examined how mortality varies jointly by age group and gender

🧠💡 Key Findings

📌 Age is the strongest risk factor: mortality peaks in the 61–80 age group

🚹 Gender disparity exists:

Male death rate ≈ 8.5%

Female death rate ≈ 3.7%

⚖️ Males consistently show higher mortality across all age groups

🇨🇳 China reports the highest number of deaths in the dataset

📉 Deaths peak early in the timeline, followed by a sharp decline

🛠💻 Tools & Technologies

Programming Language: R

Libraries Used:

dplyr

ggplot2

tidyr

lubridate

Hmisc

Output Formats:

📄 PDF Report

🌐 HTML Report (with table of contents)

📂🗃 Project Structure
COVID-19-Mortality-Analysis/
│
├── COVID19_line_list_data.csv
├── COVID-19_Mortality_Analysis.Rmd
├── COVID-19_Mortality_Analysis.pdf
├── COVID-19_Mortality_Analysis.html
└── README.md

🚀▶️ How to Run the Project

📥 Clone the repository

📂 Open the .Rmd file in RStudio

📦 Install required libraries if needed:

install.packages(c("dplyr", "ggplot2", "tidyr", "lubridate", "Hmisc"))


🧶 Knit the file to PDF or HTML

📌📝 Recommendations

🛡 Prioritize healthcare protection for individuals over 60 years old

🏥 Allocate medical resources to high-risk demographics during outbreaks

🔬 Conduct further research into biological and behavioral factors behind gender differences in mortality

👤✍️ Author

Rahma Touaibi
Junior Data Analyst | ICT Background
📅 December 2025**
