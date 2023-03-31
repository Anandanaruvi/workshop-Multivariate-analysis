# workshop-Multivariate-analysis

### AIM:

To perform multivarient analysis on the given data set.

### ALGORITHM:

### STEP1

1.Clean the data

### STEP2

2.Remove outliers

### STEP3

3.Apply the skew function and Kurtosis

### STEP4

4.Apply Bivariate analysis on numerical and categorical

### STEP5

5.Apply Multivariate analysis

### CODE: DETECTING NULL AS PD:

![image](https://user-images.githubusercontent.com/120443233/229036837-5126b688-eb1b-4b60-8dd0-6e02e6229ccf.png)

### INFO:

![image](https://user-images.githubusercontent.com/120443233/229036873-4bee1d2d-306f-4d56-ac12-d970c3876a5c.png)

### REMOVING NULL DATA:

![image](https://user-images.githubusercontent.com/120443233/229037736-5a90fed2-af36-424c-841e-01984ecf7e7d.png)

### KURTOSIS:

![image](https://user-images.githubusercontent.com/120443233/229037880-8aec6ffd-acc4-472a-b217-5f5a645b2a8e.png)

### SKEW:

![image](https://user-images.githubusercontent.com/120443233/229037999-04367e2f-316d-482f-9044-25c1a39c0416.png)

### NUMERICAL & NUMERICAL:

![image](https://user-images.githubusercontent.com/120443233/229038111-21d9bba8-4c48-4ad0-a8dc-f43c8e2eded1.png)

### NUMERICAL & CATEGORIAL:

### BOX PLOT:

![image](https://user-images.githubusercontent.com/120443233/229038219-daa50b03-1e44-4c32-9e3e-51314a1aa207.png)

### BAR PLOT:

![image](https://user-images.githubusercontent.com/120443233/229038439-587381ee-ef6c-4f81-bfd8-dde44aa14e6c.png)

### DIST PLOT:

![image](https://user-images.githubusercontent.com/120443233/229038790-bf5fa454-6b38-4910-898d-2e3158ba58d9.png)

### MULTIVARIENT ANALYSIS:

### CORRELATION:

![image](https://user-images.githubusercontent.com/120443233/229038890-7fbd101c-4305-4230-8604-418cadf30e4e.png)

### HEAT MAP:
```
import numpy as np

import seaborn as sn

import matpIotIib.pypIot as pit

data= pd.read_csv("/content/Data_set.csv")

data = np.random.randint(low = 1, high = 100, size = (10, 10)) print("The data to be plotted:\n")

print(data)

hm = sn.heatmap(data = data)

pit.show()
```
![image](https://user-images.githubusercontent.com/120443233/229039077-dab2b2bd-6a60-4821-ac2e-ee70b3a14990.png)

### Result :

Thus we applied Bivariate/Multivariate Analysis Successfully.

