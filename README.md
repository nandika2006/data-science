## ASSIGNMENT-LAB INTRODUCTION

# AIM
To apply row and column indexing using .loc and .iloc methods in Pandas to filter specific data from a dataset based on given conditions.

# Explanation
In this activity, we use Pandas, a Python library for data manipulation, to filter rows and select specific columns from a dataset containing information about bank clients.
We use the .loc method to apply conditional filtering based on column values. Some key filtering operations include:

 Selecting clients based on education level and deposit subscription status, Filtering clients based on loans, previous marketing outcomes, and employment status, Extracting specific columns like name and salary (balance) for clients under a certain age.


# Algorithm

Step 1: Load the dataset using Pandas.  
Step 2:  Inspect the dataset by checking the first few rows and column names.  
Step 3:  Apply filtering conditions according to the given query. 
Step 4:  Display the filtered results.  
Step 5:  Save or export the filtered data if needed.

# Coding and Output

ACTIVITY 1:
  1.Write a Python program to select the 'name' and 'score' columns 
  ![image](https://github.com/user-attachments/assets/fc599926-d76e-4769-9e08-00d578df83e1)

  2. For the above dataframe, Write a program to select the data who's attempt is greater than 3.
  ![image](https://github.com/user-attachments/assets/b508a601-0cab-4601-a975-9cd463c48413)

  3.  Write python code for indexing rows and columns based on the following conditions:
  Assume we have the following dataframe:
  data = {'name': ['Alice', 'Bob', 'Charlie', 'Dave'],
          'age': [25, 35, 40, 28],
          'gender': ['F', 'M', 'M', 'M'],
          'salary': [50000, 70000, 60000, 80000]}
  df = pd.DataFrame(data)
  ![image](https://github.com/user-attachments/assets/9c356454-e605-4be8-9150-4c256a5b8a68)


  a. Select rows where age is greater than 30:
  ![image](https://github.com/user-attachments/assets/912ff906-ec63-4d87-9531-eca1d42575a5)

  b. Select rows where name contains 'e':
  ![image](https://github.com/user-attachments/assets/4ab6e270-1fc6-4fda-b07a-32ef31fb9f0a)

  c. Select rows where gender is 'M' and salary is greater than 65000:
  ![image](https://github.com/user-attachments/assets/41055eec-d2c8-40b6-80f2-6f18353d48ff)

  d. Select columns 'name' and 'age'
  ![image](https://github.com/user-attachments/assets/5e93100d-225c-41dc-9e77-3905ddd8600e)

ACTIVITY 2:
 a.  select the rows where clients with primary education have subscribed to a deposit?
 ![image](https://github.com/user-attachments/assets/b7177133-3699-4cd3-98b3-80141dbee050)

 b.  select the rows where clients who have not subscribed to a deposit?
 ![image](https://github.com/user-attachments/assets/b695727d-dbcc-4823-89d7-f79df7992376)

 c. select the rows where clients who have subscribed to a deposit either have a housing or a personal loan?
 ![image](https://github.com/user-attachments/assets/1aa85a28-8451-4e29-be18-07bb1286d0ee)
 
 d. select the rows where clients with secondary education who have not subscribed to a deposit?
 ![image](https://github.com/user-attachments/assets/d5de4621-b4a1-4012-8526-085e73134252)

 e. select the rows where  clients who have subscribed to a term deposit as an outcome of the successful marketing campaign? 
 ![image](https://github.com/user-attachments/assets/eca7abec-894a-4617-a44a-e9607f6e884b)

 f. select the rows where unemployed clients who have not subscribed to deposit?
 ![image](https://github.com/user-attachments/assets/932e3083-f5b2-4a79-ac0a-be2a889bbff2)

 e. Select columns 'name' and 'salary' where age is less than or equal to 30:
 ![image](https://github.com/user-attachments/assets/449218b2-59b1-490c-a8eb-ec21831d1f67)

# Result
 Filtered the given data by the above questions or commands.






