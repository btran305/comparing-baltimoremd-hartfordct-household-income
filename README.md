# Comparing Baltimore, MD and Hartford CT's Household Income

## Background

As Hopkins students, we are well aware of the income inequality that plagued this city, but also income inequality in America overall. In this project, I want to explore how this problem manifests in Baltimore and Hartford, CT, where I previously went to school. After viewing the data, I would say the two cities seem to face the same problem where specific areas are less well-off than others, creating a clear divide. Additionally, Hartford appears to be more well-off overall, though Baltimore has a higher disparity between its lowest and highest earners.

![alt text](https://github.com/btran305/comparing-baltimoremd-hartfordct-household-income/blob/master/5ns-balvshar.png "Graph comparing the 5-num-sum for BAL and HAR")

## Data and Information Sources

1) https://www.opportunityatlas.org/ - see folder Original_datasets for the datasets used
2) https://www.census.gov/content/dam/Census/library/publications/2019/acs/acsbr18-01.pdf - used for state median
3) https://apps.urban.org/features/baltimore-investment-flows/ - disparity in Baltimore

## Data Analysis

We will look at:
1) Overview of income for different areas of the cities
2) Known low-income areas versus surrounding suburbs/towns
3) How the two cities compare with each other

## Data Manipulation

The following methods and commands were used:
1) Data summary: MIN, MAX, AVERAGE, QUARTILE (1 and 3), STDEV, COUNT, COUNTIF. Calcultion of range of data and percentage of those who make above mean. Applied histogram.
2) Looking at neighborhoods: PivotTable to consolidate neighborhoods and average income. Applied column chart.
3) Comparing the cities: VLOOKUP to obtain data summary and compare. Applied T-test. Applied column chart.
