# Fannie Mae Mortgage Risk Analysis using R

Introduction
This project provides an in-depth analysis of Fannie Mae single-family loan performance data, comparing two pivotal years: 2007, just before the financial crisis, and 2019, a period of relative economic stability. The goal is to understand how borrower profiles, loan characteristics, and default risks have evolved over this 12-year span.

This interactive report, built with R and Shiny, allows users to explore the data dynamically, offering a granular view of the factors that influence mortgage performance.

Key Features
Interactive Data Visualization: Explore data through a user-friendly interface with dynamic maps, charts, and tables.

Comparative Analysis: Directly compare key metrics from 2007 and 2019 to identify significant trends and shifts.

Dynamic Filtering: Drill down into the data by state, credit score, debt-to-income ratio, and loan-to-value percentage.

Geospatial Insights: Visualize the geographical distribution of loan characteristics and default rates across the United States.

In-Depth Borrower Profiles: Analyze the changing demographics and financial health of borrowers over time.

Tech Stack
R: The primary language used for data analysis and manipulation.

Shiny: The framework for building the interactive web application.

Tidyverse: A collection of R packages for data science, including dplyr for data manipulation and ggplot2 for static plotting.

Leaflet: An R interface to the Leaflet JavaScript library for creating interactive maps.

DT (DataTables): An R interface to the jQuery DataTables library for creating interactive tables.

Key Insights from the Analysis
This project uncovers several critical trends in the mortgage landscape:

Improved Credit Quality: Borrowers in 2019 generally had higher credit scores compared to their 2007 counterparts, indicating a move towards more creditworthy borrowers.

Lower Leverage: The analysis reveals a decrease in loan-to-value (LTV) and debt-to-income (DTI) ratios, suggesting that borrowers in 2019 were less leveraged.

Shifting Geographic Risk: The geographic concentration of high-risk loans has shifted significantly from states like California and Florida in 2007 to other regions in 2019.

Impact of Regulation: The findings suggest that post-crisis regulatory changes have had a tangible impact on lending standards and borrower behavior.

How to Run This Project Locally
To run this Shiny application on your own machine, follow these steps:

Clone the repository:

git clone https://github.com/your-username/fannie-mae-analysis.git
cd fannie-mae-analysis

Install the required R packages:

install.packages(c("shiny", "tidyverse", "leaflet", "DT"))

Run the application:
Open app.R in RStudio and click the "Run App" button, or run the following command in your R console:

shiny::runApp()

Project Goals
The primary objective of this project was to create a powerful, data-driven tool for understanding the evolution of the U.S. mortgage market. By providing a clear and interactive comparison of borrower profiles and default risks, this analysis offers valuable insights for policymakers, financial institutions, and researchers.
