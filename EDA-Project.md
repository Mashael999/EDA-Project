# <h1>Exploratory Data Analysis Project 


# Introduction
When a high school graduate is deciding between five different colleges or more,  the rankings make it easier to determine what makes one college different from the others.

A high school graduate comes to me and asks to do a simple analysis in Quacquarelli Symmonds system ranking, and answer some questions he asked. 


# Brief about the Databset

This dataset contains rankings of the world universities by Quacquarelli Symmonds. The database contains 3 tables for each year talking about universities ranking with a thousand universities in different countries around the world. QS uses 6 factors for their ranking framework wiz. Academic Reputation, Employer Reputation, Faculty to Student Ratio, Number of citations per faculty, International Faculty, International Students. Another feature included in this data was Classification (which is not used for ranking) which included the institution's size, subject range, research intensity, age, and status. the database that is available to us is for three years began from 2017 till 2020.


# Tools
<ul>
<li>In this project I will be using SQLite and Python tools.
</ul>


# Workflow Of The Project
</ul>
<h4>Step 1 Ask Questions:
</ul>

<li> Which are the universities that have Kept their ranking over the years?</li>
<li> Which re the universities get improve over the years?</li>
<li> What is the journey of Saudi universities on the university ranking?</li>
	
</ul>
<h4>Step 2 Collect And Clean Data:
</ul>

<h5>Data Collect:
The data was searched, collected, and arranged during the past week, i have find the data from kaggle.
</ul>
Clean data:
<li>removed all the rows that contain null in overall scors column and most of the scors columns contain null, and in this dataset they put '-' as null also .
<li>changed some of the columns name to be more clear and uniform for all the tables. 
<li>changed type of some columns from objectv to float
<li> there is '=' in the first two columns i removed it. 
</ul>