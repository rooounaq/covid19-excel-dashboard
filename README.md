# COVID-19 Global Dashboard: Regional Pandemic Analysis

[![Download Excel Workbook](https://img.shields.io/badge/⬇️_Download-Excel_Workbook-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)](https://github.com/rooounaq/covid19-excel-dashboard/raw/main/MINI%20PROJECT%20DATASET%20-%20WEEK%2001.xlsx)

An Excel-based analysis of how 187 countries handled the COVID-19 pandemic during 2020–21, built from the perspective of a Junior Data Analyst at a public health agency.

![Dashboard](images/Screenshot%202026-11-26%20143311.png)

## Objective
Clean, analyze and visualize country-level COVID-19 data to find patterns in spread and recovery, and recommend focus areas for pandemic control.

## Dataset
- **187 countries** across 6 continents · **16.5M confirmed cases**
- **Columns:** Country, Confirmed, Deaths, Recovered, Active, Population, Continent, Date of First Case

## What I Did

**1. Calculated metrics**
- Death Rate = Deaths ÷ Confirmed
- Recovery Rate = Recovered ÷ Confirmed
- Infection Rate = Confirmed ÷ Population
- Risk Category using `IFS`: High (> 5%), Moderate (2–5%), Low (< 2%)

**2. Conditional formatting**
- Red highlight for death rates above 5%
- 3-color scale on Recovery Rate
- Data bars on Infection Rate
- Icon sets (↑ → ↓) for risk levels

**3. Pivot tables, charts and dashboard**
- Column chart: Confirmed vs Recovered for the top 10 countries
- Pie chart: Continent-wise confirmed case distribution
- Combo chart: Confirmed cases (columns) with Death Rate (line)
- KPI cards: total confirmed, top-10 confirmed, top-10 recovered, recovery rate

**4. Lookups**
- `VLOOKUP` to fetch a country's population
- `HLOOKUP` to fetch a country's continent

## Key Insights

| Question | Answer |
|---|---|
| Highest average recovery rate | **Asia (71.9%)**, lowest was Africa (57.9%) |
| High Risk countries | **29**, including the UK, Italy, France, Belgium, Spain, Mexico and Sweden |
| Share of cases | **North America 30%**, Asia 24%, South America 23%, Europe 17% |
| Population vs cases | Only a moderate relationship: the US, India and Brazil were high, but China stayed low despite its population |
| Most efficient handling | **Vietnam**, with 0% death rate and ~84.7% recovery rate |
| Most useful visual | Top 10 Confirmed vs Recovered column chart |

## Recommendations
- Prioritize healthcare support in the 29 High Risk countries, where death rates exceed 5%.
- Study the response models of low-death, high-recovery countries like Vietnam and Qatar.
- Strengthen recovery infrastructure in Africa and South America, which had the lowest recovery rates.

## Files
| File | Description |
|---|---|
| [`MINI PROJECT DATASET - WEEK 01.xlsx`](https://github.com/rooounaq/covid19-excel-dashboard/raw/main/MINI%20PROJECT%20DATASET%20-%20WEEK%2001.xlsx) | Full workbook: data, pivot tables, lookups, dashboard and reflections (click to download) |
| `images/` | Dashboard screenshot |

## Tools
Microsoft Excel · Pivot Tables · IF/IFS · VLOOKUP/HLOOKUP · Conditional Formatting · Charts

---
**Rounak Suraj Mallick** · [LinkedIn](https://www.linkedin.com/in/rounak-suraj-mallick/)
