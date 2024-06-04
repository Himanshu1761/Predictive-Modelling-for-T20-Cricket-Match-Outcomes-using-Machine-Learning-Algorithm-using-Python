###  Predictive-Modelling-for-T20-Cricket-Match-Outcomes-using-Machine-Learning-Algorithm-using-Python

## Overview:
The project involves an in-depth analysis of T20 Cricket Match Outcomes using a Machine Learning Algorithm. The Excel file contains two different spreadsheet named as 'Details File', 'Main Table'. The Details file contain approximately 27,000 rows and 29 columns and Main Table file contains 250 rows and 31 columns. This dataset is completely Web-Scrapped using a powerful Python Library called Beatiful Soup from the CrickBuzz
(https://www.cricbuzz.com/).

## Two different aspects of analysis are covered:
1) Ball-to-Ball Prediction: In our deatail file we have performed analysis on particular dataset and try to capture next Ball prediction using different algorithm.
2) Predict Wining Team on the basis of Team's score: We have try to analyse the wining team on the basis of both the team score and other factors. 


## Data Preparation:
In our analysis, we have undertaken a comprehensive data preparation process to ensure the dataset's quality and relevance. The data was primarily gathered through web scraping from the Cricbuzz website. Various libraries and techniques, including Beautiful Soup, Selenium, and others, were utilized to facilitate this process. Below are the detailed steps involved in our data preparation:
•	Data Collection
1)	Web Scraping with Beautiful Soup:
HTML Parsing: We utilized Beautiful Soup to parse the HTML content of Cricbuzz web pages. This involved sending HTTP requests to fetch the web pages and then extracting relevant information such as match details, scores, and player statistics.
2) Data Extraction: Specific tags and attributes were targeted to extract match-specific data. For example, match dates, team names, and run rates were extracted using Beautiful Soup’s parsing capabilities.
3)Data Cleaning
Browser Automation: For web pages with dynamic content loaded via JavaScript, Selenium was used to automate browser actions. This allowed us to interact with elements such as drop-downs, buttons, and pagination to load complete data.
Data Scraping: Selenium’s ability to execute JavaScript and wait for elements to load ensured that we captured all necessary data points.
Excel- Excel is one the most powerful tool for data cleaning purpose. Therefore for our analysis we have used excel to clean the noise in our data by filtering out those data for our analysis purpose.
4) Feature Engineering
Creating New Features:
Run Rate Difference: A new feature representing the difference in run rates between the two teams was created to provide additional insights into the match dynamics.
Winning Probability: Historical data was used to create a feature indicating the winning probability based on specific match conditions.
5)	Data Splitting
Training and Testing Sets:
Splitting the Data: The dataset was split into training and testing sets to evaluate the model's performance accurately. This ensures that the model is trained and validated on separate subsets of data, providing an unbiased assessment of its predictive capabilities.

## Exploratory Data Analysis (EDA
Exploratory Data Analysis (EDA): Conducted a thorough EDA to understand the relationships between different variables and to gain insights into crime patterns. Feature Engineering: Applied various techniques to enhance the dataset's features for better analysis. 
