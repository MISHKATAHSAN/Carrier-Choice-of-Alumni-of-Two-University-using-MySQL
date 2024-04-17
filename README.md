# Carrier-Choice-of-Alumni-of-Two-University-using-MySQL


# Alumni Career Analysis using MySQL

**Introduction**

This project focuses on analyzing the career choices of alumni from two universities, College A and College B. Understanding the career paths of alumni is crucial for evaluating the success and impact of the institutions. By analyzing data related to alumni career choices, we aim to gain insights into trends, preferences, and patterns that can inform decision-making and strategic initiatives.


**Dataset**

The dataset consists of six CSV files, each containing records of alumni from College A and College B:

•	College_A_HS: Higher Studies Record of College A

•	College_A_SE: Self Employed Record of College A

•	College_A_SJ: Service/Job Record of College A

•	College_B_HS: Higher Studies Record of College B

•	College_B_SE: Self-Employed Record of College B

•	College_B_SJ: Service/Job Record of College B


**Tasks**

1.	Create a new schema named alumni.

2.	Import all CSV files into MySQL.

3.	View the structure of the six tables.

4.	Display the first 1000 rows of each table using Python (submit the solution in a Jupyter Notebook).

5.	Import all the records of tables into MS Excel (submit Excel file for this question).

6.	Perform data cleaning on each table to remove null values and store cleaned data in views.

7.	Create views for cleaned data: College_A_HS_V, College_A_SE_V, College_A_SJ_V, College_B_HS_V, College_B_SE_V, College_B_SJ_V.

8.	Create a procedure to convert the name, father's name, and mother's name into lowercase for all views.

9.	Import the created views into MS Excel and create pivot charts for the location of alumni.

10.	Write a query to create a procedure get_name_collegeA to fetch names of all students from College A using a cursor.

11.	Write a query to create a procedure get_name_collegeB to fetch names of all students from College B using a cursor.

12.	Calculate the percentage of career choices for College A and College B alumni (Higher Studies, Self Employed, Service/Job).

    
# **How to Run the Project**

1.	Set up a MySQL database server.

2.	Create a new schema named alumni.


3.	Import the provided CSV files into MySQL.


4.	Execute the SQL commands provided for each task to perform the required analysis and data processing.

5.	Use Python to display the first 1000 rows of each table (optional).


6.	Import the cleaned data into MS Excel and create pivot charts for visualization.

7.	Execute the procedures get_name_collegeA and get_name_collegeB to fetch names of students from each college.

8.	Calculate the percentage of career choices for each college.


**Conclusion**

This project showcases the application of SQL for analyzing alumni career data and deriving valuable insights. By understanding the career trajectories of alumni from different universities, institutions can better tailor their programs and support services to meet the needs of current and future students.

________________________________________

Feel free to customize the instructions and details as needed.
