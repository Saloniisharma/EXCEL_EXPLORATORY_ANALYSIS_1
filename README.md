# Bike Buyers Exploratory Analysis in Excel


## Problem Statement

The dataset "bike_buyers" presents customer profiles and purchasing behaviors in relation to bike purchases. The goal is to identify key factors that influence bike buying decisions, with the aim of optimizing marketing strategies and sales approaches. The dataset includes variables such as:

- Demographic Information: Marital status, gender, income, number of children, and education level.
- Geographic Information: Customer regions such as Europe, North America, and Pacific.
- Lifestyle Factors: Commute distance, car ownership, occupation, and home ownership status.
- Age: Age brackets are provided to see how age influences bike purchasing.
- Bike Purchases: A binary field indicating whether a customer purchased a bike.


### Steps followed 

To transform the raw data in the bike_buyers sheet into the cleaned version found in the Working_Sheet, I followed a systematic approach. Here’s the step-by-step description of how I processed and cleaned the data:

- Step 1 : Standardizing Column Values

  In the raw bike_buyers data, certain fields, such as Gender and Marital Status, were abbreviated. For example, Gender was listed as "M" and "F", and Marital Status as "M" for married and "S" for single.
  
  
  What I did: I expanded these abbreviations into full words for consistency, transforming "M" into "Male", "F" into "Female", "M" (marital status) into "Married", and "S" into "Single".Load data into Excel, dataset is a csv file.
- Step 2 : Creating Age Brackets

  The raw data contained the Age column but lacked an age classification that would make it easier to analyze purchasing patterns by age group.

  What I did: I created an additional column called Age_Bracket, categorizing customers into three groups:
  
  
      Adolescent: Ages 0-25

      Middle Age: Ages 26-50
      
      Old: Ages 51 and above.

  This helped in segmenting customers into more meaningful categories.
- Step 3 : Eliminating Duplicates

  I checked for any duplicate entries based on customer ID.
 
  What I did: I removed duplicate entries to ensure that each row in the cleaned dataset represented a unique customer.
 By carrying out these cleaning steps, I successfully transformed the raw data into a structured, consistent dataset in Working_Sheet that’s suitable for further analysis and reporting.

- Step 4 : # Bike Buyers Exploratory Analysis in Excel


## Problem Statement

The dataset "bike_buyers" presents customer profiles and purchasing behaviors in relation to bike purchases. The goal is to identify key factors that influence bike buying decisions, with the aim of optimizing marketing strategies and sales approaches. The dataset includes variables such as:

- Demographic Information: Marital status, gender, income, number of children, and education level.
- Geographic Information: Customer regions such as Europe, North America, and Pacific.
- Lifestyle Factors: Commute distance, car ownership, occupation, and home ownership status.
- Age: Age brackets are provided to see how age influences bike purchasing.
- Bike Purchases: A binary field indicating whether a customer purchased a bike.


### Steps followed 

To transform the raw data in the bike_buyers sheet into the cleaned version found in the Working_Sheet, I followed a systematic approach. Here’s the step-by-step description of how I processed and cleaned the data:

- Step 1 : Standardizing Column Values

  In the raw bike_buyers data, certain fields, such as Gender and Marital Status, were abbreviated. For example, Gender was listed as "M" and "F", and Marital Status as "M" for married and "S" for single.
  
  
  What I did: I expanded these abbreviations into full words for consistency, transforming "M" into "Male", "F" into "Female", "M" (marital status) into "Married", and "S" into "Single".Load data into Excel, dataset is a csv file.
- Step 2 : Creating Age Brackets

  The raw data contained the Age column but lacked an age classification that would make it easier to analyze purchasing patterns by age group.

  What I did: I created an additional column called Age_Bracket, categorizing customers into three groups:
  
  
      Adolescent: Ages 0-25

      Middle Age: Ages 26-50
      
      Old: Ages 51 and above.

  This helped in segmenting customers into more meaningful categories.
- Step 3 : Eliminating Duplicates

  I checked for any duplicate entries based on customer ID.
 
  What I did: I removed duplicate entries to ensure that each row in the cleaned dataset represented a unique customer.
 By carrying out these cleaning steps, I successfully transformed the raw data into a structured, consistent dataset in Working_Sheet that’s suitable for further analysis and reporting.

- Step 4 : Creating Pivot Tables
To summarize the data meaningfully, I created several pivot tables. These tables are the core of the dashboard, helping us extract insights across multiple dimensions.

   - First, I generated a pivot table to calculate the average income for customers who purchased a bike versus those who didn’t, broken down by gender. This helped us see how income levels play a role in the decision to purchase a bike.

   ![Snap_1](https://github.com/Saloniisharma/EXCEL_PROJECTS/blob/55990e64dc706dba021d366e1af8d035f9a4683b/pivot%20table%201.png)

- Second, I created a pivot table to analyze the customer age brackets. Here, we wanted to understand which age groups—adolescent, middle-aged, or older—were more likely to purchase a bike.

![Snap_2](https://github.com/Saloniisharma/EXCEL_PROJECTS/blob/55990e64dc706dba021d366e1af8d035f9a4683b/pivot%20table%202.png)

- Third, I created a table that summarized the relationship between commute distance and bike purchasing behavior. The goal was to see if people commuting longer distances were more or less likely to buy a bike.

![Snap_3](https://github.com/Saloniisharma/EXCEL_PROJECTS/blob/55990e64dc706dba021d366e1af8d035f9a4683b/pivot%20table%203.png)

- Step 5 : Visualizing the Data with Charts:
  
1. Once the pivot tables were in place, I turned them into visualizations to make the data more digestible.

- For income, I used a Clustered Bar Chart that compares the average income of customers who purchased a bike versus those who didn’t, broken down by gender. This gives us a clear picture of how income influences purchase behavior, with men and women shown side by side.

- For age groups, I used a Line Chart to visualize how bike purchasing changes across different age brackets. The chart shows the number of buyers and non-buyers in each age group, making it easy to spot trends.

- For commute distance, I created another Line Chart to show how far customers typically commute and whether they purchased a bike. This helps us see if longer or shorter commute distances correlate with higher bike purchases.

2. Next, I wanted to make the dashboard interactive and user-friendly. That’s where the slicers come in.

- Marital Status: I added a slicer for Marital Status so users can quickly filter the data to see how purchasing trends differ between married and single customers.

- Region: I added a slicer for Region, allowing us to drill down into the data by specific geographical areas—Europe, North America, or Pacific. This helps us compare how trends vary across regions.

- Education: Lastly, I added a slicer for Education to allow filtering based on different education levels, such as High School, Bachelors, or Graduate Degree. This way, we can observe how education impacts purchasing decisions.

All of these slicers are linked to every chart in the dashboard, so when a filter is applied, all the visualizations update simultaneously, providing real-time insights.

3. I took special care to ensure that the layout  is clean, professional, and easy to navigate.

- The charts are aligned neatly, with the Average Income bar chart at the top, followed by the Age Bracket and Commute Distance charts below it. This logical flow helps users interpret the data quickly.

- The slicers are positioned on the left for easy access, ensuring the user can immediately begin filtering the data.

- I maintained a consistent color scheme and labels to make the dashboard visually cohesive and easy to interpret. The use of colors for "Yes" (bike purchased) and "No" (not purchased) helps to quickly differentiate the data points in each chart.

4. Finally, I tested the dashboard by applying the slicers and ensuring that all charts respond correctly to the filters. For example, if I filter by married customers or focus on North America, the entire dashboard updates to reflect those specific subsets of data.

Snap the dashboard ,

![Snap_4](https://github.com/Saloniisharma/EXCEL_PROJECTS/blob/d9f4efbca72192ddf711d1466f7ab54e99c85a98/Dashboard.jpg)

This project successfully cleaned, analyzed, and visualized customer data to uncover insights into bike purchasing behavior. Through a well-structured dashboard, it highlights key trends related to income, age, gender, commute patterns, and regional differences, providing a user-friendly tool for exploring these factors. The outcome equips decision-makers with valuable information to tailor marketing strategies, improve customer targeting, and drive sales growth.


