# Exploring Helicopter Prison Breaks

## Table of Content

- Introduction
- Data Collection and Preparation
  - Data Collection, Challenges and Limitations
  - Preparing Data for Analysis: Python Implementation
    - Python Libraries
    - Extract Data and convert it into Pandas DataFrame
    - Removing Redundant Columns
- Temporal Analysis
  - How many prison escapes occurred each year? Are there any notable trends or patterns over time?
  - Are there specific months or days of the week when prison escapes are more likely to happen?
- Geographical Analysis
  - Which countries have the highest number of recorded prison escapes?
- Success Analysis
  - What is the overall success rate of prison escapes in the dataset?
- Escapee Analysis
  - What is the average number of escapees per incident?
  - Who are the hardened escapee inmates?

---

## Introduction

Prison escapes have long captivated public interest, showcasing human determination and the vulnerabilities of correctional systems. This analysis delves into a dataset on helicopter prison escapes, aiming to uncover insights into the temporal, geographical, success-related, and escapee-related factors associated with these incidents.

---

## Data Collection and Preparation

The dataset was obtained from the "List of helicopter prison escapes" page on Wikipedia. The data is in tabular form, consisting of 48 rows and 6 columns. All columns are in the object data type, except for the 'Escapee(s)' column which contains missing values.

Potential challenges and limitations include biases and underreporting, particularly in countries with restricted media or limited access to information. The accuracy and completeness of the data may also be influenced by the reliability of the sources used. Mistakes in reporting or categorization could impact the analysis.

### Python Libraries Used
- requests
- BeautifulSoup
- datetime
- pandas
- matplotlib
- matplotlib.pyplot
- collections.defaultdict
- re
- unicodedata
- numpy

### Data Preparation Steps
- Extracted data from Wikipedia and converted it into a Pandas DataFrame.
- Removed redundant columns (e.g., 'Details') to streamline analysis.
- Added a new column 'Failure' to indicate unsuccessful escape attempts.

---

## Temporal Analysis

### How many prison escapes occurred each year?

By grouping the data by year, we can identify trends and patterns. Notable years with high escape occurrences include 1986, 2001, 2007, and 2009.

### Are there specific months or days of the week when prison escapes are more likely to happen?

December ranked higher when analyzing prison escapes per month. Monday and Thursday ranked higher in prison escapes per day of the week.

---

## Geographical Analysis

### Which countries have the highest number of recorded prison escapes?

France has the highest recorded helicopter prison escapes, followed by other countries with fewer incidents.

---

## Success Analysis

### What is the overall success rate of prison escapes in the dataset?

Analyzing the 'Succeeded' and 'Failure' columns reveals the proportion of successful and failed escape attempts. A high success rate may indicate weaknesses in security measures, while a low success rate suggests effective security protocols.

---

## Escapee Analysis

### What is the average number of escapees per incident?

On average, about 1.8 (approximately 2) inmates are involved in any escape plan.

### Who are the hardened escapee inmates?

Some individuals, such as Pascal Payet, Michel Vaujour, and Vassilis Paleokostas, attempted helicopter prison escapes multiple times, demonstrating extraordinary determination and audacity.

---

## Conclusion

This analysis of helicopter prison escapes has revealed patterns, trends, and insights into the phenomenon. The findings highlight the importance of robust security measures and continuous improvement in correctional systems. The knowledge derived from this analysis can assist authorities in developing targeted strategies to prevent prison escapes and safeguard public safety.

---

Connect with me on [Github](https://github.com/Chukwuebuka-2003), [LinkedIn](https://www.linkedin.com/in/chukwuebuka-ezeokeke-911236194/) and [Twitter](https://twitter.com/ebukagaus).

Thank You.
