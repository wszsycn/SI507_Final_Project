## SI 507 Final Project

## Introduction
The goal of this project is to create a web application that provides users with information about cities in the United States and data visualizations for restaurants in those cities. To achieve this, we utilize several programming techniques such as caching, web API scraping, SQLite data manipulation, unit testing, and data visualization with Plotly and Flask. With these techniques, we aim to efficiently access and manage data, verify our code's functionality, and present our findings in a clear and engaging way.![image](https://user-images.githubusercontent.com/79834399/233642884-6b4d9206-c381-4cbd-a402-c0f5b3b9e9ef.png)


## Data Sources
(1) The web from Wikipedia, which is the data source for the table "Cities" in the database. (https://en.wikipedia.org/wiki/List_of_United_States_cities_by_population). 

(2) Yelp Fusion, which is the data source for the table "Restaurants" in the database.
(https://www.yelp.com/developers/documentation/v3/business_search)

## Run the Program
### Step 1: Apply an API Key for Yelp Fusion
(1) Go to "https://www.yelp.com/developers/documentation/v3/authentication" and create your app according to the instruction. 

(2) Create a new python file "secret.py" in the same folder as "program.py". And add the code:
```
API_KEY = '<your key>'
```  
### Step 2: Install packages
```
$ pip install -r requirements.txt --user
```  

### Step 3: Run program.py  
```  
$ python program.py
```  
### Step 4: Open "http://127.0.0.1:5000/ " in a browser
