# workshop-Multivariate-analysis
AIM:

To perform multivarient analysis on the given data set.

ALGORITHM:

1.Clean the data

2.Remove outliers

3.Apply the skew function and Kurtosis

4.Apply Bivariate analysis on numerical and categorical

5.Apply Multivariate analysis

CODE: DETECTING NULL AS PD:

![image](https://user-images.githubusercontent.com/95408668/192780400-c0fb5019-b2d7-49b2-977b-8f394511a115.png)

INFO:

![image](https://user-images.githubusercontent.com/95408668/192780458-cfb2650b-632e-4fc5-bfc7-c54c76f3b24d.png)

REMOVING NULL DATA:

![image](https://user-images.githubusercontent.com/95408668/192780523-802e79d6-fc88-45fa-ad08-ccc900309ef3.png)

KURTOSIS:

![image](https://user-images.githubusercontent.com/95408668/192780584-fd3b5500-435a-476e-bd47-8ffd0b91731b.png)

SKEW:

![image](https://user-images.githubusercontent.com/95408668/192780676-0efc2fea-842f-4599-9ba2-ef27be0246d8.png)

NUMERICAL & NUMERICAL:

![image](https://user-images.githubusercontent.com/95408668/192780745-e53e6140-fd85-4f5c-8405-9c245ed529cf.png)

NUMERICAL & CATEGORIAL:

BOX PLOT:

![image](https://user-images.githubusercontent.com/95408668/192780802-89d894c7-c434-47da-921c-592555e845e9.png)

BAR PLOT:

![image](https://user-images.githubusercontent.com/95408668/192780892-21ceeac3-3f57-40e0-9dc4-e00ee07e390a.png)

DIST PLOT:

![image](https://user-images.githubusercontent.com/95408668/192780956-dbf0810c-fdbd-4195-bb70-9f0c7d8519a3.png)

MULTIVARIENT ANALYSIS:

CORRELATION:

![image](https://user-images.githubusercontent.com/95408668/192781026-928fbb78-2b96-40be-b14f-c258342a1540.png)

HEAT MAP:

import numpy as np

import seaborn as sn

import matpIotIib.pypIot as pit

data= pd.read_csv("/content/Data_set.csv")

data = np.random.randint(low = 1, high = 100, size = (10, 10)) print("The data to be plotted:\n")

print(data)

hm = sn.heatmap(data = data)

pit.show()

![image](https://user-images.githubusercontent.com/95408668/192781284-0f32ae72-08a2-482d-ac67-1cc66fe253e0.png)

