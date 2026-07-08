# CODEALPHA-TASK-4-SENTIMENT-ANALYSIS-

# Section A: Project Overview

This project performs sentiment analysis on news articles using Natural Language Processing (NLP) techniques. The analysis classifies text data into into positive,negative and neutral.The aim is to create an analysis that gives a glimpse into the sentiment involved in a project.

KEY OBJECTIVES 

•	Classification of article text into different categories

•	Analyze sentiment patterns involved in the analysis.

•	Generate Insights for marketing and advertising department.

•	Discover event-driven sentiment results

# Section B: Dataset Description

The dataset (Web_Scrapping_Task.csv) consists of snippets from newspaper articles with the following features

PRIMARY COLUMNS :

•	Text: Content from the actual articles

•	Cleaned_Text:preprocessed text ready for analysis 

•	Category: Possible categories of news : sports,Current Affairs etc.

•	Source: URL root of the article involved 

•	Sentiment: This is the product of the sentiment analysis involving textblob.

DATASET CHARACTERISTICS:

•	20+ news articles analysed

• Articles mostly gotten from the source Vanguard Nigeria

•Articles mostly about sports 

 # Section C: Methodology
INSTALLATION AND SETUP:
bash

pip install openpyxl textblob

pip install vaderSentiment  

DATA PROCESSING STEPS:

1.	Data Loading
   
o	Import CSV file using Pandas

o	Preview data structure

2. Text Preprocessing 
   
o	Utilize pre-cleaned text column (Cleaned_Text)

o	Remove unnecessary noise and special characters

3.Sentiment Classification :

4.	Results Storage :
o	Add sentiment column to dataframe

o	Export results to CSV file: Cruz_Tech_Sentiment_Analysis_Results.csv

# Section D :  Summary Statistics
SENTIMENT ANALYSIS

Sentiment	Count	Percentage

Positive	12-	60%

Negative	3	-15%

Neutral	5-	25%

KEY FINDINGS

•	Most Positive Topic: PSG'S goals and offensive moment.

•	Most Negative Topic: Arsenal's Missed Chances and Defeats.

•	Primary Source: Vanguard Nigeria

•	Predominant Sentiment: Generally positve opinion towards the game performance.






