# Ex.No: 01A PLOT A TIME SERIES DATA
###  Date: 12/8/25

# AIM:
To Develop a python program to Plot a time series data (population/ market price of a commodity
/temperature.
# ALGORITHM:
1. Import the required packages like pandas and matplot
2. Read the dataset using the pandas
3. Calculate the mean for the respective column.
4. Plot the data according to need and can be altered monthly, or yearly.
5. Display the graph.
# PROGRAM:
```
import numpy as np
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
df=pd.read_csv("IMDB Top 250 Movies (1).csv")
df.head()
plt.figure(figsize=(10, 5))
sns.histplot(df['year'], bins=15, color='slategray')
plt.title("Distribution of IMDb Ratings", fontsize=14, fontweight='bold')
plt.xlabel("Year")
plt.ylabel("box_office")
plt.grid(False)
plt.tight_layout()
plt.show()
```


# OUTPUT:
<img width="1301" height="616" alt="image" src="https://github.com/user-attachments/assets/422fa868-5971-4b3b-ae8f-3ac9e22ec9a4" />






# RESULT:
Thus we have created the python code for plotting the time series of given data.
