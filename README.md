# Read-from-CSV

## AIM:

## ALGORITHM:
### Step 1:import pandas as pd
### Step 2:read the use theb csv file using read_csv
### Step 3:print the head of the file using head function
### Step 4:print the tail part of the file using tail function
### Step 5:if you want print the number of rows and columns using the following function

## PROGRAM:
# Program to read the contant from a csv file<br>
# Developed by : Sanjay sivaramakrishnan M<br>
# regester number : 23013798<br>

import pandas as pd <br>

x=pd.read_csv(r'C:\Users\admin\OneDrive\for python\py\pandas.py\data.csv')<br>

print(x.head())<br>
print(x.tail())<br>
print('Number of rows : ',len(x.axes[0]))<br>
print('Number of columns : ',len(x.axes[1]))<br>
<br>
## OUTPUT:
![image](https://github.com/sanjaysivaramakrishnan/Read-from-CSV/assets/151629616/a001fa0e-380b-40e0-acd6-765acef9b2f8)

## RESULT:
