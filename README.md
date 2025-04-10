# PRODIGY_ML_01
import pandas as pd
from sklearn.linear_model import LinearRegression as lr
from sklearn.metrics import mean_squared_error
d = pd.DataFrame({'SquareFootage': [1500, 2000, 1800, 2500, 2200],'Bedrooms': [3, 4, 3, 5, 4],'Bathrooms': [2, 2, 1, 3, 2],'Price': [300000, 400000, 350000, 500000, 450000]})
d
x = d[['SquareFootage', 'Bedrooms', 'Bathrooms']]
y = d['Price']
print(x)
print(y)
