# Read-from-CSV

## AIM:
To Write a program to read a csv file.
## ALGORITHM:
### Step 1:
Import pandas module as pd
### Step 2:
Read a csv file
### Step 3:
Print the first five rows and last five rows
### Step 4:
Print the length of the rows and columns
### Step 5:
End the program
## PROGRAM:
```
# Write a program to read a csv file
# Developed by : AARON I
# Reference no : 23002289

from google.colab import drive
drive.mount('/content/drive')

import pandas as pd
df=pd.read_csv('/content/drive/My Drive/cars (1) (7).csv')
print(df.head())
print(df.tail())
print("Rows",len(df.axes[0]))
print("Columns",len(df.axes[1]))
```
## OUTPUT:
![output](/Screenshot.png)
![output](/csv.png)
## RESULT:
Thus the program is written to read a csv file.
