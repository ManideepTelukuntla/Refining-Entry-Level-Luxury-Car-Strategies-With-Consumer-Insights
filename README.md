# Reshaping-Luxury-Car-Strategies-with-Consumer-Insights

## Table of contents
1. [Description](#1-description)
2. [Questions](#2-questions)
3. [Overview](#3-overview)
4. [Data](#4-data)
5. [Conclusions](#4-conclusions)
​
## 1. Description 
In this project, we analyzed Entry-Level Luxury Car Forum discussions. Using data scraping and Lift Analysis, we identified popular brand comparisons and attributes discussed. Further, we assessed consumer aspirations through brand mentions linked with aspiration-indicative words.
​
## 2. Questions
- Task 0:
1. Write a scraper using Python to fetch messages posted in Edmunds.com discussion forums. The
scraper output should be a .csv file with the following columns: date and message (even though
you will only use the messages in your analysis). Before you develop the scraper, carefully study
one of the forums on Edmunds.com to understand the html design as well as the threading
structures.
2. Fetch around 5000 posts about cars from the Entry Level Luxury forum
https://forums.edmunds.com/discussion/2864/general/x/entry-level-luxury-performance-sedans
- Task A:
  Once you fetch the data, test if the data support Zipf’s law econometrically. Additionally plot the
most common 100 words in the data against the theoretical prediction of the law. For this question, do
not remove stopwords. Also do not perform stemming or lemmatization.
- Task B:
  Find the top 10 brands from frequency counts. You will need to write a script to count the
frequencies of words (stopwords should NOT be counted). Replace frequently occurring car models with
brands so that from now on you have to deal with only brands and not models. You will need another
script for this job. A list of model and brand names (not exhaustive) are provided in a separate file. Even
if a brand (e.g., BMW) is mentioned multiple times in a message, it should be counted as 1.
- Task C:
  Calculate lift ratios for associations between the top-10 brands identified in Task A. You will have
to write a script to do this task). For lift calculations, be sure not to count a mention more than once
per post, even if it is mentioned multiple times in the post. In your code, ensure that a message is not
counted in the lift calculations if the mentions of two brands are separated by more than, say, 5 or 7
words.
- Task D:
  Show the brands on a multi-dimensional scaling (MDS) map (use a Python script for MDS, there
are multiple scripts available on GitHub).
- Task E:
  What insights can you offer to your client from your analyses in Tasks C and D?
- Task F:
  What are 5 most frequently mentioned attributes or features of cars in the discussions? Which
attributes are most strongly associated with which of these 5 brands? There is no need to plot the MDS
plot for this question.
- Task G:
  What advice will you give to your client from Task F?
- Task H:
  Which is the most aspirational brand in your data in terms of people actually wanting to buy or
own? Describe your analysis. What are the business implications for this brand?
​
## 3. Overview

## 4. Data
Data files necessary for conducting the analysis are:
- DiscussionData.csv
- car_models_and_brands.csv

## 5. Conclusions 
A holistic view of the data shows a clear demarcation between luxury and mainstream brands. While luxury brands excel in attributes like aspiration and sportiness, mainstream brands are more evenly spread across various attributes. There's an opportunity for brands to leverage their strengths and address their weaknesses. For instance, Cadillac could look into improving the perception of their engine quality. Similarly, Audi, with its cross-segment appeal, could strategize to target a broader consumer base. Brands should also explore partnerships based on high lift values to tap into complementary market segments.

