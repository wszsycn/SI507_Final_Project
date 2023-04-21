## SI 507 Final Project

## Introduction
The goal of this project is to create a web application of restaurant searching system that provides users with information about restaurants in cities and states in United States. To achieve this, we utilize several programming techniques such as caching, web API scraping, SQLite data manipulation, and data visualization with Plotly and Flask. With these techniques, we aim to efficiently access and manage data, verify our code's functionality, and present our findings in a clear and engaging way.


## Data Sources
Yelp Fusion, which is used as the data source for the "Restaurants" table in the database. The relevant API endpoint is (https://www.yelp.com/developers/documentation/v3/business_search).


Wikipedia, which provides the data for the "Cities" table in the database. The relevant page is (https://en.wikipedia.org/wiki/List_of_United_States_cities_by_population). 



## Run the Program
### 1: Apply an API Key for Yelp Fusion
(1) Go to "https://www.yelp.com/developers/documentation/v3/authentication" and create your app.

(2) Create a new python file "secret.py" in the same folder as "program.py". And add the code:

Well, actually you can use my secret.py, which is in this repo. 
```
API_KEY = '<your key>'
```  
### 2: Install packages
```
$ pip install -r requirements.txt --user
```  

### 3: Run program.py  
```  
$ python program_shaozhi.py
```  
### 4: Open "http://127.0.0.1:5000/ " in a browser


## Demo Video:

