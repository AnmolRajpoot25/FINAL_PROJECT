# Analysis of the product’s data scrapped from amazon
The process of inspecting, cleansing, transforming, and modeling data with the goal of discovering useful information, informing conclusions, and supporting decision-making.
How to Run this on your machine 
First download the amazon data file from the repository  and upload it on your google drive 
Then login on google collab (ignore if your are friendly with collab )
Mount your drive to that current notebook in which you are executing this project
During reading the csv file from the drive you can check the correct  path of the file which you have downloaded from the repository (named as amazon.csv)
# what is done in the project 
## Call the important Libraries 
### Numpy :- 
It provides a high-performance multidimensional array object, and tools for working with these arrays. It is the fundamental package for scientific computing with Python.
### Matplotlib.plyplot :-
Python is the most used language for Matplotlib is a plotting library for creating static, animated, and interactive visualizations in Python. Matplotlib can be used in Python scripts, the Python and IPython shell, web application servers, and various graphical user interface toolkits like Tkinter, awxPython, etc.
### Seaborn :-  
Seaborn is an amazing visualization library for statistical graphics plotting in Python. It provides beautiful default styles and color palettes to make statistical plots more attractive. It is built on top matplotlib library and is also closely integrated with the data structures from pandas.
### Pandas :-
Pandas is a Python library used for working with data sets. It has functions for analyzing, cleaning, exploring, and manipulating data.
### basic operation on the read CSV file  such as cleaning formatting converting the cleaned data in numeric data type for the operation of the libraries 
 ### design the plot using seaborn 

## Web scrapping :-
It is an automatic method to obtain large amounts of data from websites. Most of this data is unstructured data in an HTML format which is then converted into structured data in a spreadsheet or a database so that it can be used in various applications.
Check out my WEB SCRAPPING SCRIPT WHICH IS EDITABLE 
https://github.com/AnmolRajpoot25/web_scrapping_script
# CONCLUSION BY THIS PROJECT 
## Comparision of actual_price and discounted price
 #### HISTOGRAM 
 #### SCATTERPLOT 
## which product is most loved products by the customer
#### Average Rating of Products by Product ID
####  Distribution of Ratings by Product ID
 
 ## removing the ₹ and % symbol and making data operatable for numpy operation
##   most liked article:- considered the element having rating more than 4.5 is termed to be impressive product
####   discount_percentage vs rating
#### NO. OF PRODUCTS Vs RATING
##  most loved product:- actual_Prices , discounted price VS rating

##   most unlike Product:- the product having rating less thab 2.5
####    most unlike Product actual price comparison
##   Product which perform fair :- rating above 4.0 and below 4.5
#### articles perform fair with discounted price
#### articles perform fair with Actual_price

 ##   Product having High Discount:- discount above 85%
####  articles with high discount with actual_price
#### articles with high discount with discounted_price
## best Loved product:-product having less discount(<25%) but high rating (4.5)
 
####  best Loved product with Actual_price
####  best Loved product with discounted_price

##  Product needed a proper acknowlegement or products which creates negative impact :- (discount >40%), rating(<2.5)
#### articles needed proper acknowlegement with actual_price 
#### articles needed proper acknowlegement with discounted_price
## Best article on site to sell
####  actual_price vs discounted_price

  
