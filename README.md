# Glassdoor Data Science Jobs Insights
#### Exploratory Data Analysis of Data Science Jobs scraped from Glassdoor
#### By Nzinga Eduardo

### Motivation
I am a US based Data Scientist looking to make a major lifestyle change which includes living abroad and looking for remote or hybrid opportunities. In order to best prepare for the next opportunity, I thought it would be best to review popular job search engines to see which companies were best reviewed by their employees and offered the best work-life balance, benefits and salaries across different countries. I am applying for entry/junior level positions and want to know whick skills I would need to develop or freshen up before applying for the job.

This project is inspired by [Nikhil Bahti](https://github.com/dsNikhilds/Project_13-Data-Scientist-Salary-Glassdoor) and [Ken Jee](https://github.com/PlayingNumbers).

### Instructions
### Table of Contents
1. Project Overview
2. Web Scraping
3. Data Wrangling
4. Exploratory Data Analysis

### 1. Project Overview
Data Science is one of the fastest growing fields in tech. It combines multiple fields, including statistics, scientific methods, artificial intelligence (AI), and data analysis, to extract values from data. In this project I scraped job postings related to Data Science field from www.glassdoor.com in U.S only. The motive was to look at different factors like job location, company revenue, company size, etc that affect the salary of jobs related top data science.

I scraped remote or hybrid job postings related to Data Science field from [Glassdoor](www.glassdoor.com). I used a modified version of Nikhil Bahti's selenium code because that code was not working raw for me. Selenium was used because it has small chance of getting caught by glassdoor as it mimics a human kind of interaction. Sending too many request could still increase chances of getting IP block, this limited the dataset to only 1000 jobs.

The project consists of three main notebooks:
- jobs_scrapper.ipynb: Contains the python code to scrape the data from glassdoor website.
- glassdoor_preprocessing.ipynb: Cleaning and combining data scrapped in jobs_scrapper.ipynb
- data_science_jobs_insights.ipynb: EDA on data cleaned in glassdoor_preprocessing.ipynb


### 2. Web Scraping
### 3. Data Wrangling
### 4. Exploratory Data Analysis
