# workshop-Multivariate-analysis

# AIM:

To perform multivarient analysis on the given data set.

# ALGORITHM:

# STEP1

1.Clean the data

# STEP2

2.Remove outliers

# STEP3

3.Apply the skew function and Kurtosis

# STEP4

4.Apply Bivariate analysis on numerical and categorical

# STEP5

5.Apply Multivariate analysis

# CODE: DETECTING NULL AS PD:

![Screenshot 2023-04-05 180840](https://user-images.githubusercontent.com/121165938/230085642-f301046d-799f-4357-9e29-9b8671552374.png)

# INFO:

![Screenshot 2023-04-05 180856](https://user-images.githubusercontent.com/121165938/230085932-ae931f54-a01e-4979-8a48-469b8a6d7d3b.png)

# REMOVING NULL DATA:

![Screenshot 2023-04-05 180910](https://user-images.githubusercontent.com/121165938/230086148-3b5c30ce-3846-4fb9-91e7-6a44967e62d2.png)

# KURTOSIS:

![Screenshot 2023-04-05 181215](https://user-images.githubusercontent.com/121165938/230086469-2b560ec9-d80b-4374-84ed-dffc43e77ed0.png)

# SKEW:

![Screenshot 2023-04-05 181254](https://user-images.githubusercontent.com/121165938/230086694-7e5202ff-5e3d-4815-bc3b-a0eb17b6f125.png)

# NUMERICAL & NUMERICAL:

![Screenshot 2023-04-05 181352](https://user-images.githubusercontent.com/121165938/230086945-e369b811-67fc-4d81-a887-8553a0a82584.png)

# NUMERICAL & CATEGORIAL:

# BOX PLOT:

![Screenshot 2023-04-05 181515](https://user-images.githubusercontent.com/121165938/230087803-ce1038d6-d6b9-4c88-a383-eeff6d19b159.png)

#BAR PLOT:

![Screenshot 2023-04-05 181540](https://user-images.githubusercontent.com/121165938/230088908-ec0e8ff1-96d8-4ed5-bfe0-681067583df3.png)

# DIST PLOT:

![Screenshot 2023-04-05 181614](https://user-images.githubusercontent.com/121165938/230089050-ad2a593b-daa5-431e-8c14-7455415b0b3b.png)

# MULTIVARIENT ANALYSIS:

# CORRELATION:

![Screenshot 2023-04-05 181622](https://user-images.githubusercontent.com/121165938/230089277-e6652652-511e-4749-9842-e48b3f255315.png)

# HEAT MAP:

```import numpy as np

import seaborn as sns

import matplotlib.pyplot as pit

data= pd.read_excel("/content/FlightInformation.xlsx")

data = np.random.randint(low = 1, high = 100, size = (10, 10))

print("The data to be plotted:\n")

print(data)

hm = sns.heatmap(data = data)

pit.show()
```

![Screenshot 2023-04-05 181501](https://user-images.githubusercontent.com/121165938/230089956-01d0210a-7c69-43a4-8ae7-cca0517d28e2.png)

# Result :
Thus we applied Bivariate/Multivariate Analysis Successfully.


