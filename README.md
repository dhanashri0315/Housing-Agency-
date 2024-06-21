# Housing-Agency-
# task :
This code will:

Load the dataset from the provided URL.
Display the first few rows of the dataset to give you an overview of the data.
Show information about the dataset, including the number of entries, column names, and data types.
Provide basic statistics for each column.
Describe each column based on the provided descriptions.
Check for any missing values in the dataset.
Display the data types of the columns.

# task 2:
Findings:

1. Boxplot of Median Value of Owner-Occupied Homes:
   - The boxplot for the median value of owner-occupied homes (MEDV) shows the distribution of home values.
   - The presence of outliers can be observed, indicating some homes have significantly higher or lower values compared to the rest.

2. Bar Plot of Charles River Variable:
   - The bar plot for the Charles river variable (CHAS) shows the number of towns that are bounded by the river.
   - Most towns are not bounded by the river (CHAS=0), with fewer towns being bounded by the river (CHAS=1).

3. Boxplot of MEDV vs AGE Group:
   - The boxplot for MEDV vs AGE group shows the distribution of home values across different age groups of homes.
   - Homes that are 35 years and younger tend to have a higher median value compared to older homes.

4. Scatter Plot of Nitric Oxide Concentrations vs Proportion of Non-Retail Business Acres per Town:
   - The scatter plot shows a positive relationship between nitric oxide concentrations (NOX) and the proportion of non-retail business acres (INDUS).
   - As the proportion of non-retail business acres increases, the nitric oxide concentration tends to increase.

5. Histogram of Pupil to Teacher Ratio:
   - The histogram for the pupil to teacher ratio (PTRATIO) shows the distribution of this variable across towns.
   - The distribution appears to be somewhat normal with a peak around the middle range of the data.


# task 3:
Question 1: T-test for Independent Samples

Hypothesis:
𝐻0 : There is no significant difference in the median value of houses bounded by the Charles river (CHAS=1) and those that are not (CHAS=0).
𝐻1: There is a significant difference in the median value of houses bounded by the Charles river (CHAS=1) and those that are not (CHAS=0).
Conclusion: Based on the p-value, we either reject or fail to reject the null hypothesis.

Question 2: ANOVA

Hypothesis:
𝐻0: There is no difference in the median values of houses (MEDV) for each proportion of owner-occupied units built prior to 1940 (AGE).
𝐻1: There is a difference in the median values of houses (MEDV) for each proportion of owner-occupied units built prior to 1940 (AGE).
Conclusion: Based on the p-value from the ANOVA table, we either reject or fail to reject the null hypothesis.

Question 3: Pearson Correlation

Hypothesis:
𝐻0: There is no relationship between Nitric oxide concentrations (NOX) and proportion of non-retail business acres per town (INDUS).
𝐻1: There is a relationship between Nitric oxide concentrations (NOX) and proportion of non-retail business acres per town (INDUS).
Conclusion: Based on the p-value, we either reject or fail to reject the null hypothesis.

Question 4: Regression Analysis

Hypothesis:
𝐻0: There is no impact of weighted distance to the five Boston employment centres (DIS) on the median value of owner-occupied homes (MEDV).
𝐻1: There is an impact of weighted distance to the five Boston employment centres (DIS) on the median value of owner-occupied homes (MEDV).
Conclusion: Based on the p-value for the DIS variable, we either reject or fail to reject the null hypothesis.
