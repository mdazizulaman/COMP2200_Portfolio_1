# portfolio-part-1-mdazizulaman
portfolio-part-1-mdazizulaman created by GitHub Classroom
# E-commerce Dataset Analysis
This project involves the analysis of a combined e-commerce dataset, which includes user ratings, reviews, and various details about the products purchased. The goal is to explore the data, perform descriptive statistics, visualisation, and outlier detection.
## Data Cleaning
### Remove Missing Data:
* Records with missing values in columns 'gender', 'rating', and 'helpfulness' were removed.
* Rows with 'review' equal to 'none' were excluded.
* Length of the data was tracked before and after cleaning.
## Descriptive Statistics
### Dataset Summarization:
* Unique counts of users, reviews, items, and categories were computed.
* Descriptive statistics for rating records were calculated (total, mean, std, min, max).
* Statistics for the number of items rated by different genders were analysed.
* Statistics for the number of ratings received by each item were examined.
## Plotting and Analysis
### Correlation Analysis:
* Box plots were used to visualise the relationship between gender, helpfulness, category, and ratings.
* The distribution of ratings by gender was compared.
  *  Male and Female distribution is same according to the box plot.
## Outlier Detection and Removal
### Outlier Detection:
Outlier records were identified based on three rules: 
* Reviews of which the helpfulness is no more than 2
* Users who rate less than 7 items
* Items that receives less than 11 ratings
Records that met any of these rules were considered outliers.
## Summary
This analysis delves into a comprehensive e-commerce dataset. It covers data cleaning, descriptive statistics, visualisation, and outlier removal. The project provides insights into user behaviour, product ratings, and relationships between factors like gender, helpfulness, and category. The results can guide further decision-making in the e-commerce domain.
