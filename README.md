# Apple-iPhone-Sales-Analysis

import pandas as pd
import numpy as np
import plotly.express as px
import plotly.graph_objects as go
pd.read_csv("apple_products.csv")
data
print(data.isnull().sum())    #to check the missing va[Uploading apple_products.csv…]()
lue
print(data.describe())   #for statistical Analysis


# iPhone sales top 10 high rated phone

highest_rated = data.sort_values(by = ["Star Rating"], ascending = false)
highest_rated = highest_rated.head(10)
print(highest_rated [ 'Product Name'])

# Number of rating of highest rated iphone on flipkart



