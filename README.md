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

iphone = highest_rated [ "Product Name" ].value_counts()
labels = iphones.index
counts = highest_rated[ "Number Of Ratings" ]
figure = px.bar(highest-rated, x= labels, y = counts, title = "Number of ratings of highest rated iPhones")
figure.show()

# Number of rating of highest rated iphone on flipkart

iphone = highest_rated [ "Product Name" ].value_counts()
labels = iphones.index
counts = highest_rated[ "Number Of Reviews" ]
figure = px.bar(highest-rated, x= labels, y = counts, title = "Number of Reviews of highest rated iPhones")
figure.show()

# Scatter Plot

figure = px.scatter( data_frame= data, x= "Number Of Ratings", y= "Sale Price", size= "Discount Percentage", trendline= "ols", title= "Relationship between sale price and number of ratings")
figure.sho()




