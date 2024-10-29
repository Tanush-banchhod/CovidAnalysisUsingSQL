# COVID-19 Data Analysis Project

**Created by Tanush Banchhod in 2022**

## Overview
This project is a comprehensive analysis of COVID-19 data using SQL. The data includes COVID-19 case counts, deaths, and vaccination information across various locations worldwide. The project performs exploratory data analysis and calculates specific metrics, such as infection and death rates relative to population, vaccination progress, and other vital statistics. 

The project utilizes SQL queries to pull insights from COVID-19 datasets for better visualization and understanding of the impact of the pandemic globally and regionally.

## Datasets
- **CovidDeaths**: Contains records of COVID-19 cases, deaths, and population data by location and date.
- **CovidVaccinations**: Contains records of COVID-19 vaccination data by location and date.

## SQL Scripts and Features

1. **Sorting and Filtering**  
   - Sorted data for CovidDeaths and CovidVaccinations tables by location and date.
   
2. **Cases and Deaths Analysis**  
   - Calculated total cases vs. total deaths to determine the likelihood of dying.
   - Calculated infection rate by comparing total cases to the population size.
   
3. **Highest Infection and Death Rates**  
   - Identified countries with the highest infection rates relative to population.
   - Listed countries and continents with the highest death counts.

4. **Global COVID-19 Statistics**  
   - Aggregated global numbers for new cases and deaths per day, calculating daily death percentage.

5. **Joining Tables**  
   - Joined `CovidDeaths` and `CovidVaccinations` to view vaccination data in relation to cases and deaths.

6. **Rolling Vaccination Data (Using CTE)**  
   - Created a CTE (Common Table Expression) for a rolling count of vaccinated individuals, by location and date, relative to the population size.
   
7. **Temporary Table Creation**  
   - Created a temporary table to store vaccination progress as a percentage of the population.

8. **Data Visualization View**  
   - Created a view `PercentPopulationVaccinated` to simplify visualizations, summarizing the vaccination rollout across locations.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/COVID19-Data-Analysis.git

2. Execute the SQL scripts in your preferred SQL environment.

3. Use the PercentPopulationVaccinated view to connect with visualization tools like Power BI or Tableau for enhanced insights
