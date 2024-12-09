# hcde-410-final
This the repo for all final project assignments in HCDE 410 AUT24.

# Studying the influence of COVID-19 cases on streaming service usage, specifically on Disney+.

My final project will analyze the correlation between COVID-19 case trends and streaming service usage on the major platform, Disney+ in peak and post-pandemic years (2021-2024). The main research goal is to understand how a global crisis like COVID-19 influenced streaming and media consumption patterns over time. By using correlation analysis and data visualizations such as bar charts, I hope to quantify and identify key patterns throughout the pandemic, especially relationships between COVID-19 cases and subscription counts (both new and active). This study aims to provide insights into how a global crisis can change consumer behaviors in the context of digital media consumption.

**All Datasets Used**
* [Daily COVID-19 Data (2020-2024)](https://www.kaggle.com/datasets/abdoomoh/daily-covid-19-data-2020-2024) - from Kaggle but sourced from WHO
    * This dataset includes multiple files, but I will be using the WHO-COVID-19-global-data.csv: Daily reported cases and deaths by country. The relevant variables that I will be focusing on for this project are date reported in the format dd/mm/yyyy and number of cumulative cases. Since both of the datasets that I will be using are based on multiple countries, I will not be focusing on any specific regions or locations, but rather global results as a whole. It provides comprehensive, daily records of confirmed cumulative cases reported globally. The data is organized by country and covers the entire pandemic timeline from 2020 to 2024, allowing for detailed trend analysis across peak and post-pandemic periods. Another important point is that the dataset's standardized format is derived from the World Health Organization's reports, ensuring reliability. 
    * License:
        * [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0) 
---

* [Subscription Data Disney+](https://www.kaggle.com/datasets/albeyee/subscription-data-disney) - from Kaggle
    * This dataset includes information about Disney+ user subscriptions and related details. The relevant variables that I will be using for this project are user ID, join date, and last payment date. The dates are in the format mm/dd/yyyy. The data provides detailed insights into Disney+ subscriptions, encompassing usage patterns and revenue metrics. This information is essential for analyzing how global events, such as the COVID-19 pandemic, have influenced media consumption behaviors. I will combine statistics regarding active and new subscriptions with global COVID-19 cases to see if there are any relationships.
    * License:
        * [MIT](https://www.mit.edu/~amini/LICENSE.md)