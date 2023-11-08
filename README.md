
# Project Introduction: Web Scraping and Data Cleaning of Weather Data

### Introdution
In this project, we aim to gather weather data from a website and subsequently clean the dataset.

Source data: https://www.bgc-jena.mpg.de/wetter/

### Implementation Process:
- First, scrape data from the website.

file code: Craw_data.ipynb

After the scraping process, we obtain the following results.

![image](https://github.com/lonGDiBo/Crawl-Weather-Dataset-And-Cleaning/assets/115699195/e0e499fa-92e1-4ec3-b055-032ee7c890bd)


Afterward, we merge all the extracted and cleaned .csv files into one file named "Weather_dataset_Cleaning.csv."
+ Result below
![image](https://github.com/lonGDiBo/Crawl-Weather-Dataset-And-Cleaning/assets/115699195/a163222a-1dc9-4086-975c-832b8558d2ef)


- Secondly, we will clean the dataset.

Rename columns

Normalize certain columns such as Date Time, P, ...

Remove certain columns.

+ Result below
![image](https://github.com/lonGDiBo/Crawl-Weather-Dataset-And-Cleaning/assets/115699195/ab9e9f56-d1d7-408f-9278-818683ffa00f)

###  In the future, we will perform time series forecasting using an FFNN model based on the cleaned dataset.
