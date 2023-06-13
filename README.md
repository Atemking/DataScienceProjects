# ANALYSIS FOR A  SUPERMARKET DATA ACROSS THE COUNTRY FOR THE COMPANY OR SUPERMARKET CALLED XYZ USING PANDAS ANALYTIC

  I use pandas analytics to analyse a supermarket data which have branches accross three major cities
  in the country.This analysis is to help us get insight on market trends as the supermarket sector is 
  becoming more competitive. From the analysis I could derive various information like the branch which recorded 
  more sales, what product line customers buy the most ,  and the time of the day which customers start buying
  at the supermarket. Aside from all the above observation which i got from the analyses. the are many more information
  which i derived from the data provided and all this information can be use to make important business decision to increase
  more sales and for the growth of the supermarket. 

## Project Steps :

###  Step 1 : Loading the Dataset. 
  In this part of project, I had to read cvs files from each of the three major branch in the country. These files where been
  stored in a directory which i read through all of them and stored them in a DataFrame.  Before been able to read the files. 
  i had to import certain core Libraries which help me to access the files. These are the Libraries which i use below. 
 * **import os**
 * **import glob**
 * **import pandas as pd**
 * **os.chdir("/mydir")**
     
   
###  Step 2 :  Data Exploration .
  
  After I had successfully stored the data provided accross the three major cities in a dataframe, I had to explore the data to get 
  insight and to understand what the data is saying. I used the following libraries below for data Exploration
 * **import pandas as pd**
 * **import numpy as np**
 * **import seaborn as sns**
 * **import matplotlib.pyplot as plt**
 * **%matplotlib inline**
 * **plt.style.use('fivethirtyeight')**  
 * **import warnings**
 * **warnings.filterwarnings('ignore')**
     
 * I loaded the few records of the data set using  the head function in pandas.
 * I checked the number of rows and columns using the shape function in pandas.
 * I generated the names of all columns using the column attribute.
 * I did a statistical summary of the data provided using the describe function.
 * I did check if the were missing values in the data using both the isnull and notna function
 * I also use the info function to get concise summary of the data.
  
### Step 3 : Dealing with DateTime Features.
  
  I work on the datetime features , the date was not in the datetime format, so i had to convert it . 
  before doing that i had to import the datetime library below 
 *    **import datetime as dt**
  after that i proceeded by converting the date and time provided in the data to datetime and later 
  extracted various component from the datetime which i converted for further analyses. 
  I extracted the Hours , Year, Day ,Month and made a column of each of this variable into the dataset 
  
### Step 4 : Unique Values in Columns .
  
  To be able to work with unique columns, i started by testing all key values in the columns of object type. 
  those which were object where then stored in a list. 
  after that i proceeded to extract unique values of each column which was been stored in the list element. 
  
  I then did a value_count of them to get the total number of unique entries in the data provided. 
  
 
### Step 5 : Aggregration with GroupBy .
  
  I used the groupby function in pandas to group the city column so that i could perform more analyses on it . 
  after grouping the city i then perform the sum function on it and the mean to get more result and statitics 
  about the data presented. 
  
###  Step 6 - Data Visualization.
  
  After all the analyses  i had to view my data on a plot to get more better understanding of each conclusion which was derived
  
 * **I use countplot to determine the branch with the highest sales**
 * **I use countplot to determine the most payment method use**
 * **I use countplot to determine the city with the highest gross income**
 * **I use countplot to determine the most sold and least sold product line** 
 * **I use countplot to determine the payment channel use the most by customers of each branch**
 * **I use the catplot to see how gender affect the type of product which the buy**
  
  
  
  
## Insights :

  I had allot of difficulties when i was working  with the glob function which i imported , but i successfully got it right.
  I also face allot of difficulties working the datetime format , as it was quite trickish getting the Hour , minutes , second
  because i realise after some analyses. the time was showing me it type as an object , which i could not index to return the 
  corresponding information which i needed. But after allot of reasearch i successfully got it right. 
  I also had difficulties working with the unique function in pandas. it wasnt easy getting all the unique values of all the columns 
  specied , after much reasearch i succeeded.
  
## Future Work :
  
  I am looking at doing more projects related to these and also i will be using different plot functions in seaborn
  to get more better understanding of the data. 
  


## Step 7 - StandOut Section
  
  I went further to explore the data provided  to get the months which recorded the highest sales and also had
  the most gross income. 
  I then had a visualization to see the relationship between gross income and quantity of product been sale monthly
  

  
  
  
