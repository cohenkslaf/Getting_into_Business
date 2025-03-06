# Getting_into_Business

# Real Estate Investment Data Exploration by Kasey Cohen

## Overview
In this project, I analyze U.S. real estate data from 2000 to 2023 to uncover key trends, insights, and investment opportunities. The analysis explores various attributes of properties, such as price, size, location, and age, and evaluates their impact on house prices. Through statistical analysis and visualizations, this project aims to provide a solid understanding of the U.S. housing market and its investment potential.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/cohenkslaf/Getting_into_Business/blob/main/Data_Understanding.ipynb)


## Table of Contents
1. [Introduction](#introduction)
2. [Data Acquisition](#data-acquisition)
3. [Data Summary & Initial Insights](#data-summary--initial-insights)
4. [Data Visualizations & Analysis](#data-visualizations--analysis)
5. [Additional Data Sources](#additional-data-sources)
6. [Conclusion & Investment Insights](#conclusion--investment-insights)

## Introduction
Real estate investment decisions are heavily influenced by understanding the factors that drive housing prices. This project explores a comprehensive dataset of U.S. housing prices, covering various property attributes like area, number of bedrooms and bathrooms, location, and more. The analysis aims to uncover trends over time and identify correlations between property attributes and house prices.

## Data Acquisition
- **Time Range**: 2000 - 2023 (23 years of real estate data).
- **Geographical Coverage**: Multiple states across the United States, including urban, suburban, and rural areas.
- **Data Source**: Kaggle (Dataset Link) - The data was aggregated from public real estate records, platforms like Zillow and Redfin, and government property databases.

## Data Summary & Initial Insights
This dataset contains key attributes that provide valuable insights into real estate transactions:
- **Price**: Sale price of the property (in USD).
- **Area**: Total livable area of the property (in square feet).
- **Bedrooms**: Number of bedrooms.
- **Bathrooms**: Number of full and half bathrooms.
- **Location**: The city, town, or neighborhood of the property.
- **Year Built**: The year the property was originally constructed.
- **Latitude and Longitude**: Geographic coordinates of the property.

The dataset is loaded and processed in Python using Pandas for analysis and visualizations.

## Data Visualizations & Analysis
Key visualizations include:
- **Distribution of House Prices**: A histogram showing the frequency of homes in different price ranges.
- **Price vs Area**: A scatter plot to examine the relationship between house prices and property size.
- **Correlation Heatmap**: A heatmap showing the correlations between different attributes like price, area, and bedrooms.

## Additional Data Sources
An additional dataset from the U.S. Housing Market & Interest Rates is used to complement the analysis. This dataset includes historical interest rates, which can be used to predict future housing price trends. Mortgage rates are directly related to home affordability and can help investors make informed decisions.

- [U.S. Housing Market & Interest Rates Dataset](https://www.kaggle.com/datasets)

## Conclusion & Investment Insights
- **Key Findings**:
  - House prices strongly correlate with property size (area) and the number of bedrooms.
  - The median house price is around $350,000, with most properties falling in the $300K-$400K range.
  - Interest rates play a significant role in home affordability, and their fluctuations can influence market demand.

- **Investment Strategy**:
  Monitoring interest rates alongside property price trends can help investors time their investments effectively. Combining these data points with regional market insights provides a more accurate prediction of future price movements.

## Open This Notebook in Google Colab
To view and run this project, click the link below to open the notebook in Google Colab:


## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


