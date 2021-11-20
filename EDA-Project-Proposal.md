# <h1>Exploratory Data Analysis Project 


## Introduction
#### When a high school graduate is deciding between five different colleges or more, the rankings make it easier to determine what makes one college different from the others. A graduate comes to me and asks to do a simple analysis in Quacquarelli Symmonds system ranking, and answer some questions he asked.


## Brief about the Databset

#### This dataset contains rankings of the world universities by Quacquarelli Symmonds. The database contains 3 tables for each year talking about universities ranking with a thousand universities in different countries around the world. QS uses 6 factors for their ranking framework wiz. Academic Reputation, Employer Reputation, Faculty to Student Ratio, Number of citations per faculty, International Faculty, International Students. Another feature included in this data was Classification (which is not used for ranking) which included the institution's size, subject range, research intensity, age, and status. the database that is available to us is for three years began from 2017 till 2020.


## Tools
<ul>
<li>In this project I will be using SQLite and Python tools.
</ul>


## Methodology

### Step 1 Ask Questions:
</ul>
<li> The top 5 countries that contain most of the universities.
<li> Which are the universities that have Kept their ranking over the years?</li>
<li> Which are the universities get increased over the years?</li>
<li> What is the journey of Saudi universities on the university ranking?</li>


### Step 2 Data Collect:
</ul>
<li> The data was searched, collected, and arranged during the past week, i have find the data from kaggle.	

### Step 3 Call Dataset:
</ul>
<li> Call up all the libraries in python that i want to use in my project.
<li> call my dataset using SQL query. 

### Step 4 Clean Dataset:
</ul>
<li>removed all the rows that contain null in overall scors column and most of the scors columns contain null, and in this dataset they put '-' as null also.
<li>changed some of the columns name to be more clear and uniform for all the tables. 
<li>changed type of some columns from objectv to float.
<li>there is '=' in the first two columns i removed it. 
<li>Convert the wightspace in the Institution_Name columns to '_'.
<li>in the third coulmn the 'Institution_Name' is in lower case so i convert to upper case.
<li>Merge all the tables by the name of the unversties by creating a new tabel.
<li>After i done cleaning the dataset i realize tht i need a specific columns so i will drop the columns that i do not need.
<li>Rearrange the columns in the final table.
</ul>

### Step 5 Discraibe and visualize:
</ul>
