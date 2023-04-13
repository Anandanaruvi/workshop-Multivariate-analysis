### workshop-Multivariate-analysis

### AIM:

To perform multivarient analysis on the given data set.

### ALGORITHM:

1.Clean the data

2.Remove outliers

3.Apply the skew function and Kurtosis

4.Apply Bivariate analysis on numerical and categorical

5.Apply Multivariate analysis.

### CODE

Name:A.ARUVI

REG NO:212222230014

## Bivariate Analysis
```
import pandas as pd
import seaborn as sns
df=pd.read_csv("FlightInformation.csv")
df

df.isnull().sum()

df.info()

df['Route']=df['Route'].fillna(df['Route'].mode()[0])
df['Total_Stops']=df['Total_Stops'].fillna(df['Total_Stops'].mode()[0])
df.isnull().sum()

sns.scatterplot(x=df["Price"],y=df["Airline"],data=df)

sns.boxplot(x=df['Price'],y=df['Source'],data=df)

sns.barplot(x=df['Price'],y=df['Destination'],data=df)

sns.displot(df,x="Source",hue="Destination")
```
## Multivariate Analysis 
```
df.corr()import numpy as np

import seaborn as sns
import matplotlib.pyplot as plt
df= pd.read_csv("FlightInformation.csv")
df= np.random.randint(low = 1, high = 100, size = (10,10))
print("The data to be plotted:\n")
print(df)
hm = sns.heatmap(data=df)
plt.show()
```

### OUTPUT

### Bivariate Analysis

### DATA SET

![image](https://user-images.githubusercontent.com/120443233/231785704-94361997-11b2-4cec-a62d-6a21e68f0fca.png)

### INFO

![image](https://user-images.githubusercontent.com/120443233/231785799-061acb18-0c90-4846-93ef-6067fd73916d.png)

### DETECTING NULL AS PD

![image](https://user-images.githubusercontent.com/120443233/231785993-f2f60cdd-fdab-4dc3-81ec-1ed8d0f42ceb.png)

### REMOVING NULL DATA

![image](https://user-images.githubusercontent.com/120443233/231786096-75c7adb3-a9b0-41db-be68-9635cd74f8ef.png)

### NUMERICAL & NUMERICAL:

### SCATTER_PLOT

![image](https://user-images.githubusercontent.com/120443233/231786364-b073941d-d42e-40f7-91d7-13dd755dfc89.png)

### NUMERICAL & CATEGORIAL:

### BOX PLOT

![image](https://user-images.githubusercontent.com/120443233/231786556-5331b2a1-0f19-423e-8a49-ac037ecff198.png)

### BAR PLOT

![image](https://user-images.githubusercontent.com/120443233/231786789-d19c5a98-7e13-448f-be10-27a4d64b4993.png)

### DIST PLOT

![image](https://user-images.githubusercontent.com/120443233/231786947-b0e84358-31f0-42e0-a578-5b752da465ac.png)

### MULTIVARIENT ANALYSIS

### CORRELATION

![image](https://user-images.githubusercontent.com/120443233/231787136-37554db5-9bdc-4841-997d-a33d72a45496.png)

### HEAT MAP

![image](https://user-images.githubusercontent.com/120443233/231787273-353934b4-0ea2-4c55-95de-6180a8591e60.png)

### RESULT

Thus the Bivariate and Multivariate analysis is observerd for the given data set.





