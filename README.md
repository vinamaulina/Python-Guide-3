# Python_For_Data_Analytic_Part3s

## Numpy 

NumPy (Numerical Python) is a Python library that focuses on scientific computing. NumPy has the ability to create N-dimensional array objects, which are similar to lists in Python. The advantage of NumPy arrays compared to lists in Python is that they consume less memory and run time faster.

![image](https://github.com/AryantoRheynaldySaragih/Python_For_Data_Analytic_Part3s/assets/147115152/5c716fc1-16b4-421b-9ce8-bf7f94320d3a)

## Dimension In Arrays
A dimension in arrays is one on level of array dapth (nested arrays).

1.  Create a 1-D array
   
![image](https://github.com/AryantoRheynaldySaragih/Python_For_Data_Analytic_Part3s/assets/147115152/34f788ea-8499-4adb-a23e-1edb3d2286df)

2.Create a 2-D array

![image](https://github.com/AryantoRheynaldySaragih/Python_For_Data_Analytic_Part3s/assets/147115152/cb782272-4633-476d-bfab-afd6801bb2e7)

3.  Create a 3-D array with two 2-D arrays, both containing two arrays
   
![image](https://github.com/AryantoRheynaldySaragih/Python_For_Data_Analytic_Part3s/assets/147115152/3373fb46-0aec-4e0c-82db-d6a94c3e2cbe)

## Pandas
Pandas is an open-source Python library that provides high-performance data manipulation and analysis tools.Pandas have 2 objects that are Series and Data Frame.We can import the Pandas library and save it with the alias pd with the query below :

![image](https://github.com/AryantoRheynaldySaragih/Python_For_Data_Analytic_Part3s/assets/147115152/3143216f-8e5a-490b-afab-d520dbdd0a85)

## Series
Series is a one-dimensional labeled array that can hold data of any type. It doesn't have a column name because it has only one column. And also has index.We can convert the data into a series with the following query

![image](https://github.com/AryantoRheynaldySaragih/Python_For_Data_Analytic_Part3s/assets/147115152/a408a8d8-1c1c-494b-b1b3-706909f099be)

## Index
- The index is a range, where the start point is inclusive in the range, and the end point is exclusive from the range.
- We can define the indices ourselves, which are called explicit indices, and they are the ones that we specify. When defining indices, 
  the number of indices must match the number of data points.
- This data selection. Even though we have defined explicit index, we can still call the implicit index.

![image](https://github.com/AryantoRheynaldySaragih/Python_For_Data_Analytic_Part3s/assets/147115152/5ccdd46d-7964-4ab9-8f4d-652a16f6450b)

![image](https://github.com/AryantoRheynaldySaragih/Python_For_Data_Analytic_Part3s/assets/147115152/07de7be9-5420-4e9c-950e-c049910336cf)

![image](https://github.com/AryantoRheynaldySaragih/Python_For_Data_Analytic_Part3s/assets/147115152/93dbf216-5b6b-4073-b2f5-4c9a37cb702c)

## Loc And Iloc
The loc and iloc functions in Pandas are used to slice a data set. The function .loc is primarily used for label indexing, while . iloc is mainly used for integer indexing.

1.  Selecting and slicing using loc :
   
![image](https://github.com/AryantoRheynaldySaragih/Python_For_Data_Analytic_Part3s/assets/147115152/dc2dc08c-9651-4779-956b-9803b0009aaf)

2.  Selecting and slicing using Iloc :
   
![image](https://github.com/AryantoRheynaldySaragih/Python_For_Data_Analytic_Part3s/assets/147115152/efa2a475-bedb-440a-a0a2-1e55ee691a55)

## Data Frame
DataFrame is a 2-dimensional labeled data structure with columns of potentially different types. You can think of it like a spreadsheet or SQL table, or a dict of Series objects. It is generally the most commonly used pandas object.

1. To create data frame first step,we created 3 data series, namely nilai, jumlahsiswa, and kode for a subject. The 3 data series can be seen bellow :

- Data Series 1
  
![image](https://github.com/AryantoRheynaldySaragih/Python_For_Data_Analytic_Part3s/assets/147115152/674e0865-d744-42ce-9c96-e0824b77659f)

- Data Series 2
  
![image](https://github.com/AryantoRheynaldySaragih/Python_For_Data_Analytic_Part3s/assets/147115152/ce0069bb-b17c-41fc-8283-80d5d4ca6ed5)

- Data series 3
  
![image](https://github.com/AryantoRheynaldySaragih/Python_For_Data_Analytic_Part3s/assets/147115152/7c6da3d7-5f7b-4805-b1b9-3b39efddb453)

2.  Next,to create a data frame from these 3 series we need to use the pd.DataFrame format as below :

![image](https://github.com/AryantoRheynaldySaragih/Python_For_Data_Analytic_Part3s/assets/147115152/52786c30-4c0b-49c1-b49d-f0bd26a22617)


## Slicing Data From Data Frame
Sometimes generating a simple Series doesn’t accomplish our goals. For more complex operations, Pandas provides DataFrame Slicing using “loc” and “iloc” functions.

![image](https://github.com/AryantoRheynaldySaragih/Python_For_Data_Analytic_Part3s/assets/147115152/bc6b5040-f292-47ca-afd8-6c32cf7563d4)

### Dataset
Dataset typically refers to a structured collection of data that is organized and stored for the purpose of analysis, processing, or machine learning tasks. 

1. Import Dataset to Jupyter Notebook
   
![image](https://github.com/AryantoRheynaldySaragih/Python_For_Data_Analytic_Part3s/assets/147115152/eab5a077-29bf-4841-98e4-8a9f47b43666)

2. View The Top 10 Data
   
![image](https://github.com/AryantoRheynaldySaragih/Python_For_Data_Analytic_Part3s/assets/147115152/d5e122c7-c855-4b86-a9cc-bfa76a0ac801)

3. View The Bottom 10 Data
   
![image](https://github.com/AryantoRheynaldySaragih/Python_For_Data_Analytic_Part3s/assets/147115152/4383fe0c-7122-4f70-bdbd-45ec37044dc2)

4.View Data Info From Dataset

![image](https://github.com/AryantoRheynaldySaragih/Python_For_Data_Analytic_Part3s/assets/147115152/5d0157fe-20b6-41e9-9142-fc15dcfcec35)

5.Displays information from columns in the form of numbers

![image](https://github.com/AryantoRheynaldySaragih/Python_For_Data_Analytic_Part3s/assets/147115152/8e745029-2056-4cee-a952-57220160b8c8)


### Python Mini Projects
-  Question :
   Mrs. Inge wants to determine scholarship recipients based on their academic achievement index (GPA). Mrs. Inge asks for your help in selecting scholarship recipients:

A.   Write a Python program that allows Ms. Inge to enter student names and their GPAs for 10 students in the format "Name | GPA" (example: 'Adi Alkatiri | 3.8').

B.   Based on the data entered, the program must determine the scholarship recipient's eligibility status using the following criteria : 
- If the GPA is above 3.5, then the status is "Accepted by Full Scholarship" 
- If the GPA is between 3.0 to 3.5, then the status is "Partially Accepted Scholarship" 
- If the GPA is below 3.0, then the status is "Not Accepted Scholarship“

C.   To obtain scholarship status, you are required to create a function receives parameters in the form of grades and returns the scholarship.

-  Answer :
1.  Question A
   
![image](https://github.com/AryantoRheynaldySaragih/Python_For_Data_Analytic_Part3s/assets/147115152/78f3da6e-7af8-48bd-acfa-fa1195c2d72e)

2.  Question B
   
![image](https://github.com/AryantoRheynaldySaragih/Python_For_Data_Analytic_Part3s/assets/147115152/cab11a4b-8e65-4097-8b4d-7ca13558c227)

![image](https://github.com/AryantoRheynaldySaragih/Python_For_Data_Analytic_Part3s/assets/147115152/2121d27b-8da1-424a-b51b-248fec48e7ef)

3.  Question C
   
![image](https://github.com/AryantoRheynaldySaragih/Python_For_Data_Analytic_Part3s/assets/147115152/38a90cf4-87e0-46ed-8d15-6331aed5147c)
