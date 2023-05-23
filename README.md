# Python-Project-By-Web-Scraping

Web Scraping: Company Information
This web scraping project aims to retrieve company information from a website and store it in CSV format. The project focuses on extracting data such as overall rank, company name, company code, market capitalization, share price, country name, earnings, company revenue, employee counts, and category list.

Installation
To run the web scraping script, follow these steps:

      import numpy as np
      import pandas as pd
      import requests
      from bs4 import BeautifulSoup
      import matplotlib.pyplot as plt
      import seaborn as sns
      
Usage

The script uses web scraping techniques to extract company information from a specified website.

The script retrieves data for each company and stores it in a CSV file.

The CSV file is structured with the following columns:

      Overall_Rank: The overall rank of the company.
      Company_Name: The name of the company.
      Company_Code: The company code or identifier.
      Market_Cap(Trillion/Billion(in dollar)): The market capitalization of the company in trillion or billion dollars.
      Share_Price (Dollar($)): The share price of the company in dollars.
      Country_Name: The country name where the company is located.
      Earnings(Billions(in dollar)): The earnings of the company in billions of dollars.
      Company_Revenue(Billions(in dollar)): The company's revenue in billions of dollars.
      Employee_Counts: The number of employees in the company.
      Category_list: The category or industry of the company.
      
Each company's data is stored as a separate row in the CSV file. 


Step By Step Ways after installation of library

    Download the webpage using requests

    Parse the HTML source code using Beautiful Soup library
    
    Merging all the scraped data into a single file
    
    
 Exploratory Data Analysis
 
    Perform data Preprocessing & cleaning
    
    Data Cleaning and Transform the DataType
    
  
 Data visualization
 
    Univariate Analysis
    Bivariate Analysis
    Multivariate Analysis
    
    
    
Inferences & Conclusion's :-

From above exploratory data analysis I have drawn many inference and here's a brief summary. (This summary is prepared based on the data captured from website: 'https://companiesmarketcap.com/')

The market capitalization sometimes referred as Marketcap, is the value of a publicly listed company. In most cases it can be easily calculated by multiplying the share price with the amount of outstanding shares.And in our DataFrame we scrape the values of for top companies in the world.

The essential difference between revenues and earnings is that revenues are the key indicator of the gross activity reported by a business, while earnings are the net amount left after expenses are subtracted from revenue.Our Dataset help us to see the company earning and revenue genrated in recent quater.

Some other parameters also we scrape Rank of the company based on their market cap in the world , what their current share price , and if any one intrested in buying the share they have lot to compare with No. of employee , revenue they genrated in recent quater and where they stand in the world.

And more important we able to scrape the link which is directed to the company performance sheet, any one can land there and do the research more about the company itself and draw a better conclusion one the company health in the ongoing timeframe.
 
    
References:


[1] Python offical documentation. https://docs.python.org/3/


[2] Requests library. https://pypi.org/project/requests/


[3] Beautiful Soup documentation. https://www.crummy.com/software/BeautifulSoup/bs4/doc/


[4] Pandas library documentation. https://pandas.pydata.org/docs/


[5] Web Scraping Article. https://www.toptal.com/python/web-scraping-with-python
 

[6] Working with Jupyter Notebook https://towardsdatascience.com/write-markdown-latex-in-the-jupyter-notebook-10985edb91fd



📜 Summary :


Yes, using numerous data analysis and visualisation techniques we have analysed our dataset and come up with inferences. There is still room for improvement and advanced visulisations that with which even more minute insights can be pulled out of our dataset. I will continue working and updating this note book as and when I find some time. Yes thanks for spending your valuable time on reading this notebook!


