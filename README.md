# Nigerian Health Data Analysis and Dashboard

## Objectives

- The aim of this analysis is to understand the improvement in the healthcare in Nigeria by checking the rate of change of disease prevalence, mortality and recovery over time, putting into consideration the ages and gender and socioeconomic status of the affected population.

## Process
- The main data used was gotten from KAggle. Its a World Health Statistics data by Malaiarasu G Rag, last updated in 2024.
- I downloaded the dataset, then uploaded it into MSSQL using the improt data option, after creating a database called Health Data.
- I exteracted the data for Nigeria using the sytax
- SELECT * FROM globalhealthstatistics WHERE Country = 'Nigeria'
- I clicked on the table that was queried and saved the data as Nigeria Health Data
- Here is the dataset
<a href="https://github.com/KehindeOladele/Kehinde_Project/blob/main/NHS%20Dashboard.xlsx">Nigerian_Health_Data</a>
- I created pivot table that answers the questions:
- What is the total rate of recovery?
- What is the rate of prevalence per gender?
- what is the total mortality rate and mortality rate per Age
- How is the rate of health access for each gender?
- What is the rate of prevalence of the different diseases over time.
- Here is a screenshot of the dashboard
- <a href="https://github.com/KehindeOladele/Kehinde_Project/blob/main/Screenshot%20(47).png)">Dashboard</a>

## Insights
- From the data, I saw that the rate of disease prevalence mortality and recovery has not changed much over time. This shows that more still need to be done to improve health outcomes in Nigeria
- Also, While immunization help to reduce mortality of diseases that have vaccines, mortality from surgrical treatments are higher. This emphasizes the need to improve the training of Nigerian doctors in surgery to make them more skilled thus reducing the rate of death from surgry.
