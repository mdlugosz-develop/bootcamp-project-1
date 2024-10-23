# Analysis of Contract Awards in Investment Project Financing

## Table of Contents
- [1. Introduction](#introduction)
- [2. Data Preparation](#data-preparation)
- [3. Data Cleaning and Transformation](#data-cleaning-and-transformation)
- [4. Exploratory Data Analysis](#exploratory-data-analysis-eda)
- [5. Country-Specific Analysis](#country-specific-analysis)
- [6. Forecasting with Prophet](#forecasting-with-prophet)
- [7. Regional Analysis](#regional-analysis)
- [8. Supplier and Contract Analysis](#supplier-and-contract-analysis)
- [9. Conclusion](#conclusion)

## 1. Introduction <a id="introduction"></a>

This notebook analyzes contract awards financed by The World Bank under Investment Project Financing (IPF) operations and explores the relationship between these awards and GDP growth across different regions.

### Data Sources
- [World Bank Contract Awards Dataset](https://financesone.worldbank.org/contract-awards-in-investment-project-financing/DS00005)
- [World Bank GDP Growth Indicator](https://data.worldbank.org/indicator/NY.GDP.MKTP.KD.ZG)
- [Investment Contracts CSV](https://drive.google.com/file/d/1KxbwH4l-gjjhX4GV0dVwmK5xhzbwywM8/view?usp=sharing)

# Analysis of Contract Awards in Investment Project Financing

### 2. Data Preparation <a id="data-preparation"></a>
- [Presentation](https://docs.google.com/presentation/d/1UEbeN3UVTxcIlRh5esy8SHXutRsmbPYCOvvHlp_w4Nw/edit?usp=sharing)
- **Objective**: Import necessary libraries and load datasets for analysis.
- **Actions**: 
  - Suppressed warnings for cleaner output.
  - Loaded and prepared GDP and contract awards datasets.

### 3. Data Cleaning and Transformation <a id="data-cleaning-and-transformation"></a>
- **Objective**: Prepare the data for analysis by cleaning and transforming it.
- **Actions**:
  - Converted date columns to datetime format.
  - Extracted relevant columns and filtered data.
  - Split rows with multiple values in certain columns into separate rows.

  ### 4. Exploratory Data Analysis (EDA) <a id="exploratory-data-analysis-eda"></a>
- **Objective**: Perform exploratory analysis to uncover patterns and insights.
- **Actions**:
  - Visualized data distributions using pie charts and bar plots.
  - Analyzed contract amounts by various categories and regions.

### 5. Country-Specific Analysis <a id="country-specific-analysis"></a>
- **Objective**: Focus on specific countries to analyze contract awards and trends.
- **Actions**:
  - Conducted detailed analysis for Afghanistan and India.
  - Visualized spending and project counts over time.
  - Prepared data for forecasting using the Prophet model.

### 6. Forecasting with Prophet <a id="forecasting-with-prophet"></a>
- **Objective**: Forecast future trends in contract awards using the Prophet model.
- **Actions**:
  - Fitted Prophet models to spending and contract count data.
  - Made future predictions and visualized the results.

  ### 7. Regional Analysis <a id="regional-analysis"></a>
- **Objective**: Analyze contract awards and GDP growth by region.
- **Actions**:
  - Mapped countries to regions and calculated average GDP growth.
  - Visualized GDP growth trends over time for different regions.

### 8. Supplier and Contract Analysis <a id="supplier-and-contract-analysis"></a>
- **Objective**: Analyze supplier data and contract awards over time.
- **Actions**:
  - Identified top suppliers and their contract amounts.
  - Analyzed contract awards over time for specific countries and regions.

## 9. Conclusion <a id="conclusion"></a>
This analysis provides insights into the distribution and trends of contract awards under IPF operations, highlighting the relationship with GDP growth across regions. The use of visualizations and forecasting models aids in understanding past trends and predicting future outcomes.
