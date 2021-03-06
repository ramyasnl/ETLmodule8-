# ETL</br>
## Background </br>
We have created an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. We wrote a function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data (Extraction) and performed the Transformation process by cleaning and merging the data as we need and we Load the data to a PostgreSQL database.</br>
## What We Are Creating </br>
![image](https://user-images.githubusercontent.com/76931568/128980317-09bfeea9-c067-4ee8-8557-bfef95d9a60b.png)</br>


This project consists of four technical analysis deliverables. We will submit the following:</br>

Deliverable 1: Write an ETL Function to Read Three Data Files</br>
[Click the link to view the code of Deliverable 1 ](https://github.com/ramyasnl/ETLmodule8-/blob/main/submission1.ipynb)</br>
Deliverable 2: Extract and Transform the Wikipedia Data</br>
[Click the link to view the code of Deliverable 2 ](https://github.com/ramyasnl/ETLmodule8-/blob/main/deliverable2module8.ipynb)</br>
Deliverable 3: Extract and Transform the Kaggle data</br>
[Click the link to view the code of Deliverable 3 ](https://github.com/ramyasnl/ETLmodule8-/blob/main/deliverable3submissioncopy.ipynb)</br>
Deliverable 4: Create the Movie Database</br>
![Click the link to view the Movie Datbase ](https://github.com/ramyasnl/ETLmodule8-/blob/main/Resources/movies_query.png)</br>





Note for the reader:</br>
In this project we are Extracting ,Transforming and Loading the data using Jupyter Notebook,Postgresql<br/>
Data extracted from wikimovies , kaggle are used as inputs ,output data stored in postgresql as two tables </br>
The input file ratings.csv has 26x10^6 data entries if you open it in excel you can see only 14X10^6 since excel can hold only that much data</br>
Make sure to check the size of the file after downloading and storing which can prevent mistakes .
