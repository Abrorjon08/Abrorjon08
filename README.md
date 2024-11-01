import numpy as np

d1= np.array([1,2,3,4,5,6])

d2 = np.array([[1,2,3], [4,5,6]])

sum_d1 = np.sum(d1)

sum_d2= np.sum(d2)

mean_d1= np.mean(d1)

mean_d2= np.mean(d2)

prod_d1 = np.prod(d1)

prod_d2 = np.prod(d2)

print("10 massiv:", d1)

print("20 massiv:\n", d2)

print("10 yig'indisi:", sum_d1)

print("10 o'rtachasi:", mean_d1) 

 print("1D ko'paytmasi:", prod_d1)
 
print("20 yig'indisi:", sum_d2)

print("20 o'rtachasi:", mean_d2)

print("2D ko'paytmasi:", prod_d2)

import pandas as pd
