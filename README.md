# Reshaping Luxury Car Strategies with Consumer Insights

## Table of Contents
1. [Description](#1-description)
2. [Research Questions](#2-questions)
3. [Project Overview](#3-overview)
4. [Data Resources](#4-data)
5. [Conclusions and Insights](#5-conclusions)

---

## 1. Description 
In this project, we analyzed discussions from the Entry-Level Luxury Car Forum. Utilizing data scraping and Lift Analysis techniques, we discerned prevalent brand comparisons and the attributes being discussed. Furthermore, we evaluated consumer aspirations by analyzing brand mentions associated with aspiration-indicative words.

---

## 2. Research Questions
### Task 0:
1. Develop a Python scraper to retrieve messages from Edmunds.com discussion forums. The output should be a .csv file containing columns: date and message. Study the forum's HTML structure and threading patterns before creating the scraper.
2. Extract approximately 5000 car-related posts from the [Entry Level Luxury forum](https://forums.edmunds.com/discussion/2864/general/x/entry-level-luxury-performance-sedans).

### Task A:
- Test the data's adherence to Zipf’s law econometrically and plot the 100 most common words against the law's theoretical prediction. Do not remove stopwords or perform stemming/lemmatization.

### Task B:
- Identify the top 10 brands from frequency counts. Create a script to count word frequencies (excluding stopwords) and replace common car models with brand names.

### Task C:
- Calculate lift ratios for associations between the top-10 brands from Task A. Develop a script for this task, ensuring a message is not counted more than once per post.

### Task D:
- Illustrate the brands on a multi-dimensional scaling (MDS) map using a Python script.

### Task E:
- Offer insights to your client based on analyses in Tasks C and D.

### Task F:
- Identify the 5 most frequently mentioned car attributes or features in the discussions and their strong associations with the top 5 brands.

### Task G:
- Provide strategic advice to your client based on findings from Task F.

### Task H:
- Determine the most aspirational brand in your data and discuss the business implications for this brand.

---

## 3. Project Overview
During the initial phase of the project, we focused on gathering substantial data from the Entry-Level Luxury Car Forum. This data served as a rich resource for understanding consumer preferences and discussions revolving around various car brands and their attributes.

In Task B, we conducted a frequency analysis to identify the top mentioned brands and common terms in the discussions. The analysis revealed the following brands as the most frequently mentioned:

- BMW: 2003 mentions
- Audi: 1467 mentions
- Acura: 1312 mentions
- Honda: 949 mentions
- Seat: 594 mentions
- Volkswagen: 469 mentions
- Sedan: 424 mentions
- Infiniti: 395 mentions
- Cadillac: 379 mentions
- Hyundai: 358 mentions
- Toyota: 345 mentions
- Problem: 309 mentions
- Ford: 275 mentions

Following Task B, in Task C, we utilized the data to calculate lift ratios between the top-mentioned brands. This involved creating a heatmap visualization that clearly displayed the lift scores between these brands, providing a graphical representation of the associations and relationships between them. Here is the heatmap visualization:

![Heatmap Visualization](Figures/Brand-Lift-Scores-Heatmap.png)

In Task D, we further analyzed the data through a multi-dimensional scaling (MDS) plot, which showcased two distinct clusters: luxury and non-luxury car brands. This visualization helped in delineating the perceptual differences between the brands, offering a clear picture of the market dynamics and consumer preferences. Here is the MDS plot:

![MDS Plot](path/to/your/mdsplot.jpg)

---

## 4. Data Resources
The following data files are essential for the analysis:
- DiscussionData.csv
- car_models_and_brands.csv

---

## 5. Conclusions and Insights
The data analysis reveals a distinct separation between luxury and mainstream brands. Luxury brands predominantly excel in aspects like aspiration and sportiness, whereas mainstream brands have a broader attribute spectrum. This presents an opportunity for brands to accentuate their strengths and address weaknesses. For instance, Cadillac could enhance their engine quality perception, while Audi could strategize to reach a wider consumer base. Brands might also consider forming partnerships based on high lift values to explore complementary market segments.
