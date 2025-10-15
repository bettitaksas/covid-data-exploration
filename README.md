# 🦠 COVID-19 Exploratory Data Analysis with SQL Server

This project presents an exploratory data analysis (EDA) of global COVID-19 data using **Microsoft SQL Server**. It focuses on understanding the spread, impact, and vaccination progress of COVID-19 across countries and continents, using structured queries and analytical techniques.

## 📁 Data Sources

- **CovidDeaths**: Contains daily records of confirmed cases, deaths, and population by location.
- **CovidVaccinations**: Contains daily vaccination data by location.

## 🎯 Objectives

- Analyze infection and mortality rates by country and continent.
- Compare total cases to population to estimate infection penetration.
- Track vaccination progress over time using rolling aggregates.
- Prepare clean, structured data for future visualizations and dashboards.

## 🧪 Key Analyses Performed

- Filtered and cleaned data to focus on country-level records.
- Calculated death percentages to assess the severity of outbreaks.
- Measured infection rates relative to population size.
- Identified countries and continents with the highest case and death counts.
- Aggregated global case and death trends over time.
- Joined vaccination data to compute cumulative vaccination progress.
- Used CTEs, temporary tables, and views to modularize and store results.

## 📊 Insights Uncovered

- Countries with the highest infection and death rates per capita.
- Daily and cumulative global trends in new cases and deaths.
- Rolling vaccination totals and percentage of population vaccinated.
- Regional comparisons of pandemic impact and response.

## 🛠️ Tools & Technologies

- **Microsoft SQL Server**: For data storage, querying, and transformation.
- **T-SQL**: Used for aggregations, joins, CTEs, temp tables, and views.

## 📌 Highlights

- Clean, modular SQL logic for reproducible analysis.
- Real-world metrics such as death rate, infection rate, and vaccination coverage.
- Scalable structure for integration with BI tools and dashboards.

---

💬 Feel free to fork, clone, or contribute to this project.  
Whether you're a data analyst, student, or healthcare researcher—this project offers a solid foundation for COVID-19 data exploration and storytelling.
