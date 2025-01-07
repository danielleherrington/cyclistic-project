# 🚴‍♀️ Cyclistic Case Study - Google Analytics Project

### Analysing bike-share data using R

## 📖 **Introduction**

The Cyclistic Case Study is part of the Google Analytics project, developed to analyse the data from the Cyclistic Bike-Share Programme. In this fictional scenario, a dataset of bike-sharing trips in Chicago, provided by Cyclistic, a fictional bike-share company, is used to determine the most effective ways to convert casual riders into members.

## 📊 **Project Overview**

Cyclistic is a leading bike-share company based in Chicago, USA, offering a fleet of over 5,800 bikes and 600 stations across the city. The company provides a flexible, eco-friendly transportation option for both residents and tourists. Cyclistic’s user base is divided into two main groups: annual members, who typically use the service regularly for commuting, and casual riders, who use the bikes less frequently, often for recreational purposes.

The goal of this case study is to understand customer behaviour and develop strategies for improving membership conversion. By analysing this data, we seek to provide valuable insights for the marketing team to enhance the business and increase member subscriptions.

This project analyses historical ride data to uncover insights into the behaviour and preferences of both user groups. The findings reveal key differences in how casual riders and annual members use the service. For instance, casual riders tend to use the bikes on weekends and during warmer months, often for longer, leisurely rides. On the other hand, annual members have more consistent usage patterns throughout the week, with shorter rides typically associated with daily commuting.

*Note: Due to the large size of the dataset, the data is not included in this repository. Instead, please refer to the data_instructions.md file for detailed instructions on how to obtain and prepare the data for analysis.*

## 🗂️ **Project Structure**

- [rmarkdown/](./rmarkdown): R Markdown files for data cleaning, transformation and analysis.
- [visuals/](./visuals): Plots and graphs generated during the analysis.
- [reports/](./reports): Final case study report (HTML).
- [README.md](./README.md): This file.
- [data_instructions.md](./data_instructions.md): Instructions for downloading and preparing the data.

## 🔧 **Tools Used**

This project utilises the following tools and R packages for data analysis and visualization:

- **R:** The primary programming language for data manipulation, analysis, and visualisation.
- **R Markdown**: Used to create dynamic and reproducible reports combining code, results, and documentation. It generates the README.md and final analysis report.
- **tidyverse**: A collection of R packages (e.g., `ggplot2`, `dplyr`, `tidyr`, `readr`) for data manipulation, visualisation, and analysis.
- **janitor**: Provides easy-to-use functions for cleaning data and improving data quality, particularly for handling column names and cleaning.
- **lubridate**: A package for working with dates and times, simplifying date manipulation.
- **scales**: A package for scaling and formatting data for better visualisation (e.g., custom axis labels, formatting numbers).
- **leaflet**: A package for creating interactive maps, which is particularly useful for visualising geographic data.


## 📈 **Key Findings & Recommendations**

### **Key Insights**
- Casual riders are more likely to use the service during weekends and peak summer months.
- Annual members display consistent usage patterns throughout the year, primarily for commuting during peak hours.

### **Recommendations for Cyclistic**
Based on these findings, the report provides several strategies to increase annual memberships:

- **Seasonal Promotions**: Offer time-limited discounts or membership trials during peak casual riding months (summer) to encourage conversion.

- **Targeted Marketing**: Create weekend and holiday packages to appeal to casual riders, particularly tourists, and leverage geo-targeting near popular recreational areas to drive membership sign-ups.

- **Off-Peak Offers**: Highlight the benefits of membership for non-commute hours and send personalised offers to frequent casual riders.

- **Leisure-Focused Incentives**: Promote group membership packages and discounts at local attractions to attract casual riders looking for a more flexible and social way to use the service.

By implementing these strategies, Cyclistic can increase its membership base, improve long-term customer loyalty, and strengthen its competitive position in the Chicago transportation market.

## 📄 **Report**

View the full report [here](reports/case_study.html).

## 📜 **License**

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

## 👤 **Author**

Danielle Herrington – [LinkedIn](https://www.linkedin.com/in/danielle-herrington-b6412a30a/)
