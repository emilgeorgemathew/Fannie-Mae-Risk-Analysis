# Fannie Mae Mortgage Risk Analysis using R

## Introduction

This project provides an in-depth analysis of Fannie Mae single-family loan performance data, comparing two pivotal years: 2007 and 2019. Through an interactive R Shiny dashboard, it delivers actionable insights on borrower profiles, default risks, and the evolution of the mortgage market.

## Getting Started

To set up and explore the Fannie Mae Loan Performance Analysis dashboard, follow these steps:

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/your-username/fannie-mae-analysis.git](https://github.com/your-username/fannie-mae-analysis.git)
    cd fannie-mae-analysis
    ```

2.  **Install R and RStudio:**
    Ensure you have the latest versions of R and RStudio installed on your machine.

3.  **Install Required R Packages:**
    Run the following command in your R console to install the necessary packages for the application.
    ```R
    install.packages(c("shiny", "tidyverse", "leaflet", "DT"))
    ```

4.  **Run the Application:**
    Open `app.R` in RStudio and click the "Run App" button, or run the following command in your R console:
    ```R
    shiny::runApp()
    ```

## Table of Contents

- [Overview](#overview)
- [Data Source and Pre-processing](#data-source-and-pre-processing)
- [Project Objectives](#project-objectives)
- [Key Insights](#key-insights)
- [Visualizations, Findings, and Impact](#visualizations-findings-and-impact)
- [Recommendations](#recommendations)
- [Tech Stack](#tech-stack)
- [Contents](#contents)
- [Credits](#credits)

## Overview

This project analyzes Fannie Mae's single-family loan data to compare borrower profiles and default risks between 2007, a year preceding the financial crisis, and 2019, a period of relative economic stability. The goal is to understand the evolution of lending standards and borrower behavior over this critical 12-year period. By using an interactive R Shiny dashboard, the project presents its findings through dynamic visualizations, making complex data accessible to a broad audience, from financial analysts to policymakers.

## Data Source and Pre-processing

The analysis is based on the publicly available Fannie Mae Single-Family Loan Performance Data. We focused on two specific yearly snapshots, 2007 and 2019, to capture the market before the financial crisis and in a more recent, stable period. The raw data was cleaned and processed in R to select relevant variables (such as credit score, DTI, LTV, and geographic location), handle missing values, and structure it for efficient use within the Shiny application.

## Project Objectives

- Design an interactive and user-friendly dashboard for data exploration.
- Analyze and compare trends in borrower credit scores, debt-to-income (DTI) ratios, and loan-to-value (LTV) percentages.
- Create interactive visualizations to convey insights from the raw data.
- Provide actionable recommendations for stakeholders based on the observed trends.
- Present insights on the shifting geographic concentration of mortgage risk in the United States.

## Key Insights

- **Improved Credit Quality:** Borrowers in 2019 generally had higher credit scores compared to their 2007 counterparts, indicating a move towards more creditworthy borrowers.
- **Lower Leverage:** The analysis reveals a decrease in loan-to-value (LTV) and debt-to-income (DTI) ratios, suggesting that borrowers in 2019 were less leveraged.
- **Shifting Geographic Risk:** The geographic concentration of high-risk loans has shifted significantly from states like California and Florida in 2007 to other regions in 2019.
- **Impact of Regulation:** The findings suggest that post-crisis regulatory changes have had a tangible impact on lending standards and borrower behavior.

## Visualizations, Findings, and Impact

Our interactive R Shiny dashboard provides key insights into Fannie Mae's loan performance:

1.  **Interactive US Map**
    - **Visualization:** A choropleth map of the United States displaying key metrics like average credit score, DTI, and LTV by state for both 2007 and 2019.
    - **Findings:** Visually highlights the dramatic geographical shift in risk profiles. For example, states that were epicenters of risk in 2007 show marked improvement by 2019.
    - **Impact:** Allows stakeholders to quickly identify high-risk regions and changing market dynamics, helping to allocate resources for targeted intervention or investment.

2.  **Dynamic Comparative Charts**
    - **Visualization:** A series of bar charts and histograms that dynamically update to compare key metrics side-by-side for the two years.
    - **Findings:** Quantifies the significant improvement in overall borrower creditworthiness and the reduction in leverage across the market.
    - **Impact:** Provides clear, empirical evidence of the market's evolution, informing policy, validating risk models, and guiding strategic decisions.

3.  **Filterable Data Tables**
    - **Visualization:** An interactive data table that allows users to perform granular filtering and sorting on the underlying dataset.
    - **Findings:** Enables deep-dive analysis into specific borrower segments or geographic areas that may not be apparent at a high level.
    - **Impact:** Supports detailed ad-hoc research for analysts and provides transparent access to the data driving the high-level visualizations.

## Recommendations

- **Maintain Stringent Lending Standards:** The improved credit quality in 2019 suggests that post-crisis regulations have been effective. It is recommended to maintain these standards to mitigate future default risks.
- **Continuously Monitor Geographic Risk:** As the concentration of risk shifts, new areas of concern may emerge. Continuous monitoring of geographic trends is crucial for proactive risk management.
- **Address Borrower Leverage:** Although LTV and DTI ratios have improved, they remain key indicators of risk. Financial products and counseling could be targeted at borrowers with higher leverage to support sustainable homeownership.

## Tech Stack

- **R** (Data Analysis & Manipulation)
- **Shiny** (Interactive Web Application Framework)
- **Tidyverse** (Data Science Packages, including `dplyr` and `ggplot2`)
- **Leaflet** (Interactive Maps)
- **DT (DataTables)** (Interactive Tables)
- **GitHub** (Version Control & Publishing)

## Contents

- `app.R`: The R script containing the UI and server logic for the Shiny application.
- `README.md`: This project description file.
- `data/`: Directory containing the cleaned and processed data files used by the application.

## Credits

- **Emil George Mathew** - Project Lead, Data Analysis, and Dashboard Development.
