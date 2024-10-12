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

- Step 4 :
