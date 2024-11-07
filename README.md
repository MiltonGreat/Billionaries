# Billionaires Statistics Analysis

This project is an exploratory data analysis (EDA) of the Billionaires Statistics Dataset, which includes demographic, geographic, and economic data on billionaires from various industries and countries worldwide. This project provides insights into trends related to wealth distribution, industry representation, age demographics, and the influence of economic factors on billionaire wealth.

## Project Structure

The project is organized as follows:

- **Data Extraction and Cleaning**: Load and preprocess the dataset, handling missing values and ensuring appropriate data types.
- **Feature Engineering**: Create additional features such as `net_worth_billion`, `age_group`, and `wealth_origin` to enhance analysis.
- **Exploratory Data Analysis (EDA)**: Visualize and analyze data to uncover patterns and insights.
- **Geographical and Industry Insights**: Analyze billionaire distribution by country, city, and industry, and explore relationships with economic indicators.

## Dataset

The dataset is contained in `Billionaires Statistics Dataset.zip` and includes information on each billionaire’s:
- **Personal Details**: Name, age, and wealth origin (self-made or inherited)
- **Financial Information**: Net worth, industry, and company source
- **Geographic Details**: Country, city, and geographic coordinates (latitude and longitude)
- **Economic Indicators**: Life expectancy, education enrollment, and tax rate by country

## Analysis Overview

The analysis involves the following steps:

### 1. Data Preprocessing
- **Missing Values**: Impute missing values for essential columns such as `age`, `country`, `city`, `gdp_country`, `life_expectancy_country`, and others.
- **Data Type Conversions**: Convert relevant columns (e.g., `finalWorth`, `gdp_country`) to numeric formats.
- **Feature Engineering**:
  - **`net_worth_billion`**: Convert net worth to billions for easier readability.
  - **`age_group`**: Group age into categories (`Young`, `Middle-Aged`, `Senior`).
  - **`wealth_origin`**: Categorize billionaires based on whether their wealth is `Self-Made` or `Inherited`.

### 2. Exploratory Data Analysis (EDA)
- **Distribution of Numerical and Categorical Features**:
  - Age and net worth distributions to understand demographic and financial characteristics.
  - Wealth origin and age group distributions.
- **Industry Analysis**:
  - Investigate the prevalence of billionaires across industries.
  - Identify the top industries with the highest average and total net worth.
- **Geographical Analysis**:
  - Map the geographic distribution of billionaires and visualize total net worth by country.
  - Examine the relationship between tax rates and billionaire density by country.

### 3. Key Questions Answered
- **How does billionaire net worth vary by age group and wealth origin?**
  - Younger billionaires tend to be in industries such as Technology, while older billionaires are often found in Finance and Retail.
  - Visualization of net worth by `age_group` and `wealth_origin` provides insights into the wealth accumulation patterns of self-made vs. inherited billionaires.
  
- **Is there a relationship between life expectancy and net worth?**
  - Scatter plots and correlation analyses explore whether billionaires from countries with higher life expectancies tend to have greater wealth.
  
- **Which industries are associated with younger vs. older billionaires?**
  - Box plots show age distributions within industries, revealing that Technology is more associated with younger billionaires, while Finance has older representatives.

- **What is the geographical distribution of billionaire wealth?**
  - Maps and density plots display billionaire wealth across different regions, highlighting the high concentration of wealth in the United States, China, and Germany.

## Visualizations

The following visualizations are included to enhance understanding of the data:
- **Histograms**: Age and net worth distributions.
- **Bar Charts**: Wealth origin and age group distributions, top industries by net worth.
- **Box Plots**: Net worth distribution by age group and industry.
- **Geographical Maps**: Scatter maps showing the distribution of billionaire net worth by country.

## Source

https://www.kaggle.com/datasets/nelgiriyewithana/billionaires-statistics-dataset


