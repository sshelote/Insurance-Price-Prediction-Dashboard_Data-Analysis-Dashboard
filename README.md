
# Insurance Price Prediction Dashboard

### Dashboard Link : https://app.powerbi.com/groups/me/reports/adce7fce-33a0-448c-ba10-eca21ca737f3/bd896133d5b4e214510b?experience=power-bi

## Problem Statement

The goal of this project is to build a Power BI dashboard that helps understand how different factors affect insurance prices. The dashboard analyzes customer details such as age, BMI, smoking habits, region, and other health-related factors to predict insurance costs. By identifying trends, insurance companies can price policies better, and customers can see what factors impact their insurance costs.

# Dataset Overview

The dataset contains details about individuals, including:

Age: The age of the person.

Sex: Whether the person is male or female.

BMI (Body Mass Index): A measure of body fat based on height and weight.

Children: Number of dependent children.

Smoker: Whether the person smokes or not.

Region: The area where the person lives.

Charges: The insurance cost for that person.

# Steps Followed

Step 1: Load Data into Power BI

Open Power BI Desktop.

Import the dataset (CSV file) into Power BI.

Step 2: Data Cleaning & Preparation

Open Power Query Editor.

Check for missing or incorrect values in each column.

Remove duplicate records, if any.

Ensure data types are correct (e.g., numerical for BMI and charges, categorical for sex and region).

Create new calculated columns if needed (e.g., Age groups).

Step 3: Creating Visuals

1. Insurance Cost Distribution

A histogram was created to show how insurance charges are spread across different individuals.

2. Impact of Age and BMI on Insurance Cost

A scatter plot was used to analyze the relationship between age, BMI, and insurance charges.

Older individuals and those with higher BMI tend to have higher insurance costs.

3. Effect of Smoking on Insurance Charges

A bar chart was created to compare the average insurance cost between smokers and non-smokers.

Smokers have significantly higher insurance costs than non-smokers.

4. Regional Influence on Insurance Costs

A clustered bar chart was used to compare the average insurance cost across different regions.

Differences in cost based on location were observed.

5. Family Size and Insurance Costs

A line graph was created to show the effect of the number of children on insurance charges.

Larger families had varying insurance costs based on other risk factors.

Step 4: Adding Filters & Interactivity

Added slicers for Age, BMI, Region, Smoking Status, and Number of Children.

Enabled drill-through features to allow deeper analysis based on selected criteria.

Step 5: Dashboard Formatting & Publishing

Applied a consistent colour theme.

Used appropriate labels and tooltips for better understanding.

Published the dashboard to Power BI Service for easy sharing.

# Key Insights

Smoking is the biggest cost factor: Smokers have insurance costs nearly twice as high as non-smokers.

Higher BMI leads to higher insurance charges: Overweight individuals pay more.

Older people have higher insurance costs: The cost increases with age.

Region matters: Insurance prices vary slightly depending on where a person lives.

Family size has a moderate impact: Having more children increases the insurance cost but not as much as smoking or BMI.

# Conclusion

This dashboard helps both customers and insurance companies understand how different factors influence insurance pricing. Companies can use this data to create better pricing models, and individuals can learn how to reduce their insurance costs by maintaining a healthy lifestyle.


# Snapshot of Dashboard 
https://github.com/user-attachments/assets/d3e85cdd-916b-45da-af2e-c6877b573303


