# Python_For_Data_Analytic_Part3s

## Numpy 
NumPy (Numerical Python) is a Python library that focuses on scientific computing. NumPy has the ability to create N-dimensional array objects, which are similar to lists in Python. The advantage of NumPy arrays compared to lists in Python is that they consume less memory and run time faster.

![image](https://github.com/vinamaulina/Python-Guide-3/assets/114405502/43e50056-2261-4ce1-bb66-df39f3c3ac7a)


### Dimension In Arrays
A dimension in arrays is one on level of array dapth (nested arrays).

1.  Create a 1-D array <br>
![image](https://github.com/vinamaulina/Python-Guide-3/assets/114405502/6eb57dab-d0d9-46e5-a069-d4a243db0385)

2. Create a 2-D array <br>
![image](https://github.com/vinamaulina/Python-Guide-3/assets/114405502/6ef838ad-e526-4c69-ae9d-db735c4bf55c)

3. Create a 3-D array with two 2-D arrays, both containing two arrays <br>
![image](https://github.com/vinamaulina/Python-Guide-3/assets/114405502/05b5882d-3376-43c0-8ce0-604476aeb893)


## Pandas
Pandas is an open-source Python library that provides high-performance data manipulation and analysis tools. Pandas have 2 objects that are Series and Data Frame. We can import the Pandas library and save it with the alias pd with the query below : <br>
![image](https://github.com/vinamaulina/Python-Guide-3/assets/114405502/da48bb6d-ae55-4af0-a53b-c9c77ce31b93)

### Series
Series is a one-dimensional labeled array that can hold data of any type. It doesn't have a column name because it has only one column. And also has index. We can convert the data into a series with the following query: <br>
![image](https://github.com/vinamaulina/Python-Guide-3/assets/114405502/25684d48-f4bd-4c8a-a49d-e9a838ba213b)

### Index
- The index is a range, where the start point is inclusive in the range, and the end point is exclusive from the range. Display the index: <br>
![image](https://github.com/vinamaulina/Python-Guide-3/assets/114405502/038038da-ef51-492c-8014-268e8f9feabe)

- Print the data using index: <br>
![image](https://github.com/vinamaulina/Python-Guide-3/assets/114405502/f558435b-0a41-4595-976f-fe2b62b4e1a9)

- We can define the indices ourselves, which are called explicit indices, and they are the ones that we specify. When defining indices, the number of indices must match the number of data points. <br>
![image](https://github.com/vinamaulina/Python-Guide-3/assets/114405502/6ed5844e-1314-438d-9763-a59f0d12540c)

- Print the data using explicit index: <br>
![image](https://github.com/vinamaulina/Python-Guide-3/assets/114405502/d9538723-3df2-41a8-9e40-73d7fc1651db)

- This data selection. Even though we have defined explicit index, we can still call the implicit index. <br>
![image](https://github.com/vinamaulina/Python-Guide-3/assets/114405502/c45f689c-9129-4b7d-8e95-a1c4b1a4ec4d)

### Loc And Iloc
The loc and iloc functions in Pandas are used to slice a data set. The function `.loc` is primarily used for label indexing, while `.iloc` is mainly used for integer indexing.

1.  Selecting and slicing using loc : <br>
![image](https://github.com/vinamaulina/Python-Guide-3/assets/114405502/2ffeabfe-727c-4f60-9167-4c34372a3e07)

2.  Selecting and slicing using Iloc : <br>
![image](https://github.com/vinamaulina/Python-Guide-3/assets/114405502/5cb6ea8f-bc80-443e-862f-eebf30da43c9)

### Data Frame
DataFrame is a 2-dimensional labeled data structure with columns of potentially different types. You can think of it like a spreadsheet or SQL table, or a dict of Series objects. It is generally the most commonly used pandas object.

1. To create data frame first step,we created 3 data series, namely nilai, jumlahsiswa, and kode for a subject. The 3 data series can be seen bellow : <br>

- Data Series 1 <br>
![image](https://github.com/vinamaulina/Python-Guide-3/assets/114405502/7d89410f-d906-44ec-94c4-bf272badb32b)

- Data Series 2 <br>
![image](https://github.com/vinamaulina/Python-Guide-3/assets/114405502/778648be-8552-4714-8c3d-7ddb7ef3dce5)

- Data series 3 <br>
![image](https://github.com/vinamaulina/Python-Guide-3/assets/114405502/9cd1e7f2-83f7-40ec-9d7a-90b24d1bb5d1)

2.  Next,to create a data frame from these 3 series we need to use the pd.DataFrame format as below : <br>
![image](https://github.com/vinamaulina/Python-Guide-3/assets/114405502/4456423d-1fb9-4994-81a2-2d93a3012bd3)

#### Slicing Data From Data Frame
Sometimes generating a simple Series doesn’t accomplish our goals. For more complex operations, Pandas provides DataFrame Slicing using “loc” and “iloc” functions. <br>
![image](https://github.com/vinamaulina/Python-Guide-3/assets/114405502/61f18995-9d0f-4c3c-af92-0ab620f557b5)

### Dataset
Dataset typically refers to a structured collection of data that is organized and stored for the purpose of analysis, processing, or machine learning tasks. <br>
1. Import Dataset to Jupyter Notebook <br>
![image](https://github.com/vinamaulina/Python-Guide-3/assets/114405502/7e7971dd-2125-4a72-9b2a-57a487bdabef)

2. View The Top 10 Data <br>
![image](https://github.com/vinamaulina/Python-Guide-3/assets/114405502/37caf835-6a5a-41d7-b4f7-1c4100e0e6d3)

3. View The Bottom 10 Data <br>
![image](https://github.com/vinamaulina/Python-Guide-3/assets/114405502/c04d2c30-aca0-41d5-a6bd-eee51294c57c)

4. View Data Info From Dataset <br>
![image](https://github.com/vinamaulina/Python-Guide-3/assets/114405502/16894b27-2e76-4938-b860-7f810fc8c561)

5. Displays information from columns in the form of numbers <br>
![image](https://github.com/vinamaulina/Python-Guide-3/assets/114405502/0e8c42a8-833e-4eb4-9506-552e82ce380e)

### Python Mini Projects
**Question :** <br>
Mrs. Inge wants to determine scholarship recipients based on their academic achievement index (GPA). Mrs. Inge asks for your help in selecting scholarship recipients: <br>
a.) Write a Python program that allows Ms. Inge to enter student names and their GPAs for 10 students in the format "Name | GPA" (example: 'Adi Alkatiri | 3.8'). <br>

b.) Based on the data entered, the program must determine the scholarship recipient's eligibility status using the following criteria : <br> 

- If the GPA is above 3.5, then the status is "Accepted by Full Scholarship" 
- If the GPA is between 3.0 to 3.5, then the status is "Partially Accepted Scholarship" 
- If the GPA is below 3.0, then the status is "Not Accepted Scholarship“ <br>

c.) To obtain scholarship status, you are required to create a function receives parameters in the form of grades and returns the scholarship. <br>

**Answer :** <br>
1. Question A <br>
![image](https://github.com/vinamaulina/Python-Guide-3/assets/114405502/72af16d2-c5c0-4363-bf94-b41eb77ea77d)

2. Question B <br>
![image](https://github.com/vinamaulina/Python-Guide-3/assets/114405502/07752764-b6c6-4c18-91ee-6b457feb9597) <br>
Output <br>
![image](https://github.com/vinamaulina/Python-Guide-3/assets/114405502/896eb907-9c11-49ed-9fb1-53f44fb396e6)

3. Question C <br>
![image](https://github.com/vinamaulina/Python-Guide-3/assets/114405502/a0a7a5e0-e791-4e69-bbf6-745211a67658)
