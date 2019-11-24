# Arabic-Fatwa-ChatBot
In this project, I created an Arabic Fatwa ChatBot that aims to answer a different question 

### 2.1 Scraping the Data
The data scraping was one of the most time consuming parts of this project because it’s difficult to navigate through the nested tables (the HTML). However, BeautifulSoup made it quite simple to grab the HTML and parse through it.

In this project I scraped from [islamweb.net](https://www.islamweb.net/ar/), I decided to start by scraping top of all  Fatwa  so that I could build out my chatbot. When I looked at the [page](https://www.islamweb.net/ar/fatawa) that includes all fatwas. As a first step, I noticed that I need to collect all linkes of all fatwas then  go into each fatwa to collect the needed information (Question and answer). 

### 2.2 Data Cleaning

The next focus was to clean the data to build a better chatbot. I started by importing the CSV file that I had created into my Python environment then I read this file using dataframes.Next, I worked with the variables to make sure that they were able to be processed by applied the following: 

* Remove duplicated fatwa
* Remove special charecter 
* Remove number and stop words
* Remove harakat 
* Stemming
* Shuffling Data

### 2.3 Building the Arabic chatbot
I used buildin library 


Thank you for reading!
