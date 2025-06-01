# ReDI-CO2-Emission-Project
CO₂ Emissions Analysis in the United States



Project Overview

   This project explores carbon dioxide (CO₂) emissions across the United States using public environmental data. . 
   The goal is to understand which factors contribute most to emissions and how this information could support climate-related decision making.




Motive

Climate change is one of the biggest challenges of our time. CO₂ emissions are a major contributor, and understanding their sources is key to reducing environmental impact. 
As a beginner in data science, I chose this dataset to practise skills in data cleaning, visualisation, and basic analysis while contributing to a socially relevant topic.

Source: [Kaggle - CO₂ Emissions Dataset] (https://www.kaggle.com/code/abdelrahman16/co2-emissions/input?select=emissions.csv)
- File used: `emissions.csv`
- Columns include: `year`, `state-name`, `sector-name`, `fuel-name`, and `value` 



**Data analysis**

Data Loading & Cleaning
    Loaded the CSV file using `pandas`
    Removed rows with missing values 
    Excluded the national total (`state-name = United States`) to focus on state-level data 
    

Analysis & Visualisation
Analysed trends in total CO₂ emissions over time
Identified top and bottom emitting states
Compared emissions by economic sectors (e.g., residential, transport)
Compared emissions by fuel type (e.g., coal, petroleum)
Focused on residential sector trends in selected states


Installed packages 
Pandas, Matplotlib, Seaborn



Key Findings
CO₂ emissions have decreased slightly in recent years, but large states like Texas and California still lead in total emissions.
The **residential sector** contributes significantly, showing that household energy habits matter.




Challenges

The dataset had fewer columns 




Future improvements 

Use forecasting methods to predict future CO₂ trends
Build an interactive dashboard 


