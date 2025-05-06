# Gapminder Data Analysis with PySpark

This project explores the Gapminder dataset using PySpark to analyze global development trends.  The dataset contains various development indicators like fertility rate, life expectancy, child mortality, GDP per capita, and population across different countries and regions over time.

## Project Goals

The primary objective is to perform a comprehensive Exploratory Data Analysis (EDA) using PySpark, uncovering insights into the relationships between these indicators and identifying global and regional trends.  The analysis includes data cleaning, univariate and bivariate analysis, temporal trend analysis, regional comparisons, and aggregation operations.

## Key Learnings (PySpark)

This project provided valuable experience with PySpark, highlighting the following key concepts:

1. **SparkSession:** Understanding the role of SparkSession as the entry point for Spark functionality.

2. **SQL Module Functions:**  Proficiency in using SQL module functions (e.g., `col`, `when`, `isnan`, `Window`, `Row`) for data manipulation within PySpark.

3. **DataFrame API vs. SQL:** Recognizing the performance equivalence of Spark SQL and DataFrame API for the same operations.

4. **Visualization in PySpark:**  Addressing the challenges of visualizing large datasets in PySpark (e.g., converting to pandas, `handyspark` library, aggregating results for efficient plotting).

5. **Lazy Evaluation:** Understanding lazy evaluation in PySpark and the distinction between transformations and actions.

6. **Column Objects:** Recognizing that selecting a column returns a `Column` object and using them in actions like `.show()`, `.collect()`, or `.toPandas()`.

7. **Big Data Scaling:**  Appreciating PySpark's suitability for big data analysis compared to native Python solutions.

## Dataset Description

The Gapminder dataset provides information on:

- **Country:** Name of the country.
- **Year:** Year of observation.
- **fertility:** Average number of children per woman.
- **life:** Life expectancy at birth (years).
- **population:** Total population.
- **child_mortality:** Number of deaths of children under five per 1,000 live births.
- **gdp:** Gross Domestic Product per capita.
- **region:** Geographic region or continent.

## Methodology

The analysis follows these steps:

1. **Data Cleaning:** Handling missing values, removing duplicates, correcting data types, and standardizing categorical values.  Outlier detection and treatment are also performed.

2. **Exploratory Data Analysis (EDA):**
    - **Univariate Analysis:** Summary statistics and distributions for each variable.
    - **Bivariate Analysis:** Exploring relationships between pairs of variables.
    - **Temporal Trends:** Analyzing how indicators change over time.
    - **Regional Comparisons:** Comparing indicators across regions.
    - **Aggregation Operations:** Calculating summary statistics (mean, median, etc.) grouped by different categories.
    - **Population Insights:** Analyzing population size and its relationships with other indicators.
    - **Child Mortality Analysis:** Examining trends in child mortality.
    - **Summary Tables & Visualizations:** Generating summary tables and visualizations to represent findings (heatmaps, maps, etc).

## Notebook
[Access the notebook](https://github.com/akashdv25/PySpark-EDA/blob/main/Pyspark_test%20(1).ipynb)


## Deliverables

- Cleaned and documented dataset.
- Summary statistics, aggregation tables, and visualizations.
- Insights on global and regional development trends.
- Comprehensive documentation of analysis steps and findings.
