# Crime_Forecasting_Using_Data_Science

## Dataset Overview¶
The dataset you provided seems to contain information about rape cases in different states/UTs of India from 2015 to 2020. The columns include:

Sl. No.: Serial number. State/UT: The name of the state or union territory. 2015 - CR to 2020 - CR: The number of cases reported each year from 2015 to 2020.

### Potential Hypotheses for Testing:
**Trend Analysis: Hypothesis:** The number of rape cases in a given state has significantly increased or decreased over the years from 2015 to 2020. Test: Time series analysis or a trend analysis across the years.

**State-Wise Comparison:** Hypothesis: Certain states consistently report higher numbers of rape cases compared to others. Test: Comparative analysis across states using ANOVA or other statistical tests to identify significant differences.

**Yearly Comparison: Hypothesis:** The average number of cases across all states/UTs is significantly different between certain years. Test: Paired t-test or Wilcoxon signed-rank test for comparing years, e.g., 2015 vs. 2020.

**Visualization Suggestions:**
Time Series Plot: Plotting the number of cases over the years for each state/UT to visualize trends. A line plot or area plot can effectively show trends over time.

**Heatmap:** A heatmap showing the intensity of rape cases across states/UTs and years would give a quick visual insight into which areas and years had higher cases.

Bar Plot: A bar plot to compare the total number of cases across different states for a specific year or the total number of cases summed over the years.

**Box Plot:** A box plot to visualize the distribution of cases across different states for each year, helping to identify outliers or states with consistently high/low cases.

### Exploratory Data Analysis (EDA):
For EDA, I would suggest the following steps:

**Missing Values Check:** Ensure there are no missing values in the dataset.

**Summary Statistics:** Generate summary statistics for each year to understand the spread and central tendency of the data. 

**State-wise Distribution:** Analyze the distribution of cases across states to identify patterns.

**Year-on-Year Changes:** Calculate the percentage change in the number of cases year on year for each state to identify significant increases or decreases.
