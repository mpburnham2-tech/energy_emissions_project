# Assessing emissions-reduction impacts of renewable energy in Washington State \(1960-2020)

Project: Environmental Data Science Certificate Capstone

Author: Michael Burnham

Date: March 2027

---

## OVERVIEW

This capstone project explores how shifting from consuming fossil fuel-generated energy to renewable resources can help my home state, Washington, reduce its greenhouse gas (GHG) emissions. The state has an economywide target of net zero GHG emissions by 2050, so this data analysis can help the state begin to identify the most impactful clean-energy sources and design climate mitigation policy interventions. 

## RESEARCH QUESTIONS

My hypothesis is there’s a strong correlation between using more renewable energy and reducing emissions. As I explain in greater detail below, I will analyze U.S. Energy Information Administration (EIA) data in R to test my hypothesis and answer my first question: What is the relationship between total renewable energy consumption and greenhouse gas emissions in Washington. I anticipate that answering this question will involve conducting linear regression and bivariate analysis of two variables (renewable energy consumption and GHG emissions) to produce a correlation plot and line graphs.  I will also examine per-capita emissions to provide additional context.

My second question: Which energy sources show the strongest associations with changes in emissions? I plan to examine the relationship between greenhouse gas emissions and three of the largest renewable energy sources in Washington -- hydropower, solar energy, and wind energy. I plan to conduct linear regression and bivariate analysis of each renewable energy source and GHG emissions to help answer this question.

## DATASETS

Given the availability of panel (longitudinal) data from the EIA dataset, the temporal and geographic scope of analysis for my first question will be 1960 to 2020 in the Washington. The temporal and geographic scope for my second question will be 2002 to 2020 in Washington. I plan to use the following data variables:

•	Data Variable: Annual Renewable energy consumption (in billion Btu)
•	Data Type: Numeric in tabular format (CSV)
•	Data Source: U.S. Energy Information Administration (EIA)
•	Data Time Series: 1960-2020
•	Data Geography: Washington State

•	Data Variable: Total annual energy CO2 emissions (in million metric tons of CO2)
•	Data Type: Numeric in tabular format (Excel)
•	Data Source: U.S. EIA
•	Data Time Series: 1960-2024
•	Data Geography: Washington State

•	Data Variable: Renewable energy production estimates by source -- annual (in billion Btu) [note: I will use this dataset to look separately at hydropower, wind, and solar energy]
•	Data Type: Numeric in tabular format (CSV)
•	Data Source: U.S. EIA
•	Data Time Series: 1960-2024
•	Data Geography: Washington State

•	Data Variable: Per capita energy-related CO2 emissions -- annual (in metric tons of CO2) 
•	Data Type: Numeric in tabular format (CSV)
•	Data Source: U.S. EIA
•	Data Time Series: 1960-2024
•	Data Geography: Washington State

## CAPSTONE REPOSITORY ORGANIZATION

My repository contains the following initial folders:
├── data/
│   ├── raw_data/
│   │   ├── raw_data_20261111/
│   │   │   ├── wind_energy_consumption.csv
│   │   │   ├── hydropower_consumption.csv
│   │   │   ├── solar_energy_consumption.csv
│   │   │   ├── total_energy_emissions.csv
│   │   │   ├── per_capita_emissions.csv
│   │   │   ├── total_energy_consumption_by_source.csv
│   ├── clean_data/
│   │   ├── clean_data_20261111/
│   │   │   ├── df_wa_solar_energy_consumption.csv
│   │   │   ├── df_wa_hydropower_consumption.csv
│   │   │   ├── df_wa_wind_energy_consumption.csv
│   │   │   ├── df_wa_energy_consumption_by_source.csv
│   │   │   ├── df_wa_total_energy_emissions.csv
│   │   │   ├── df_wa_per_capita_emissions.csv
│   ├── analysis/
│   │   ├── data_analysis_2026####
│   │   │   ├── #################
│   │   ├── scripts_20261109
│   │   │   ├── Project_folder_setup
│   ├── metadata/
│   │   ├── README_20251016
│   │   │   ├── README.md
│   │   ├── Background_20251016
│   │   │   ├── data_processing_notes.md
│   │   │   ├── product_info.md
│   │   │   ├── config.txt
│   │   │   ├── project_notes_jan2023.txt
│   │   │   ├── random_notes.txt
│   ├── archive/
│   │   ├── archival_scripts_10162025
│   │   │   ├── Sales_Analysis_OLD.ipynb
│   │   │   ├── quick_check.ipynb
│   ├── outputs/
│   │   ├── reports_20251016
│   │   │   ├── customer_report.txt
│   │   │   ├── employee_analysis_final.txt
• Raw data

As my capstone progresses, I plan to add other folders, including Results and Communications.

