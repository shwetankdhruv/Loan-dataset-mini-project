                                # Loan-dataset-mini-project
                              
Questions -
1. Import the dataset and understand it.
2. List down the number of rows and columns.
3. ‘Int_rate’ column is character type. With the help of lambda function
convert into float type.
4. Check the datatype of each column.
5. Cleaning the dataset- Remove the columns having complete NaN value in
the entire dataset.
6. Write the code to find the value counts of the ‘loan_status’ category
column and filter only the ‘fully paid’ and ‘charged off’ categories.
7. Filter the ‘Emp_Len’ column to extract the numerical value from the
string.
Hint - Emp_len : < 1year, 2 years , 3 years as 1 , 2, 3 so on.
8. Using the Lambda function, remove the month from the ‘term’ column
such that ‘36 months’, ‘60 months’ appear as 36 and 60 respectively.
9. Create a new column as risky_loan_applicant by comparing loan_amnt
and funded_amnt with the following criteria -
If loan_amnt is less than equals to funded_amnt set it as ‘0’ else set it as
‘1’.
10. Using the bar plot visualize the loan_status column against categorical
column grade, term, verification_status . Write the observation from
each graph.
11.Using a user defined function convert the ‘emp_len’ column into
categorical column as follows -
If emp_len is less than equals to 1 then recode as ‘fresher’.
If emp_len is greater than 1 and less than 3 then recode as ‘junior’.
If emp_len is greater than 3 and less than 7 then recode as ‘senior’
If emp_len is greater than 7 then recode as ‘expert’.
12.Find the sum of ‘loan_amnt’ for each grade and display the distribution
of ‘loan_amnt’ using a pie plot.
