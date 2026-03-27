# Pandas-DataFrame
Data cleaning and summarizing the rating of user applications project

### What was done:
1. Successfully loaded the applications.csv file into the Pandas DataFrame.
- Duplicates were removed for the applicant_id column.
- Missing values ​​in the External Rating field were filled with zeros.
- Missing values ​​in the Education level field were filled with the text "Average".
2. Data from the industries.csv file was successfully loaded and merged with the previous DataFrame.
3. The application rating was calculated according to the specified conditions:
- The rating is a number from 0 to 100.
- The rating is calculated as the sum of the ratings for 6 criteria.
- The rating is 0 if the 'Amount' value is missing or if 'External Rating' is 0.
5. Applications with a rating less than or equal to 0 were removed from the DataFrame.
6. Grouping by week of application submission was applied, and a table of the average rating of accepted applications for each week was displayed.
