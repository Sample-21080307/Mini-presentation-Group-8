# Mini-presentation-Group-8
Report of Mini presentation Group 8 
# import libraries
import pandas as pd
import numpy as np
# import data
url='./Players.csv'
df_iris=pd.read_csv(url)
df_iris.drop('Unnamed: 0',axis=1, inplace=True)
df_iris.head() 
df_iris.isna().sum()
