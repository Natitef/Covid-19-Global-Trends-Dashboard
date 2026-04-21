# COVID-19 Global Trends Dashboard

## Project Overview
This project analyzes global COVID-19 data to uncover trends in case rates, 
death counts, and vaccination rollout across countries and continents. 
The goal was to transform raw public health data into an interactive dashboard 
that non-technical stakeholders can use to understand the pandemic's global impact.

## Tools Used
- **SQL (SQL Server)** — Data extraction, cleaning, and analysis
- **Tableau Public** — Interactive dashboard and visualizations

## Dashboard Visualizations
- **Global Numbers** — Summary table showing total cases, total deaths, 
  and global death percentage
- **Total Death Per Continent** — Bar chart comparing total COVID deaths 
  across Europe, North America, South America, Asia, Africa, and Oceania
- **Percent Population Infected Per Country** — World map showing what 
  percentage of each country's population contracted COVID, color coded 
  by severity
- **Percent Population Infected Over Time** — Trend lines tracking infection 
  rates across the US, UK, Russia, India, Mexico, and China from 
  February 2020 to late 2021, including forecast estimates

## Key Findings
- Europe had the highest total death count of any continent
- The United States had the highest percentage of population infected 
  among major countries
- Global death percentage was approximately 2.11% of total cases
- The US infection rate grew significantly faster than other major 
  countries like India and China

## SQL Queries Covered
- Death percentage by country and date
- Infection rate vs total population
- Countries with highest infection counts
- Continents with highest death counts
- Rolling vaccination totals using CTEs and window functions
- Created a reusable View for vaccination data



## Dashboard
View on Tableau Public - https://public.tableau.com/app/profile/nathan.tefera/viz/CovidDashboardPortfolio_17413641976970/Dashboard1
