# Read-from-CSV

## AIM:
To read files from csv files using python program.
## ALGORITHM:
### Step 1:
First we want to import pandas.
### Step 2:
Then we want to create csv file.
### Step 3:
Both python and csv files are in the same folder.
### Step 4:
Then write the revalent code in the python file
### Step 5:
Then check the result.
## PROGRAM:
```
# To read files from csv files using python program.
# Developed by: Shalini.k
# Register no: 22008827

import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
![image](https://github.com/shalinikannan23/Read-from-CSV/assets/118656529/112a402e-d32f-40d9-bd4e-81cfb59f2108)
## RESULT:
The result for read from csv is came successfully
