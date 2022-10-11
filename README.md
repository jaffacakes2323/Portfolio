# Portfolio

Data Analysis


## [Project 1: June 2022 Oil Price Analysis](https://github.com/jaffacakes2323/oil_price_scraping)

### Collecting Data
- [Downloaded data from Kaggle for analysis](https://www.kaggle.com/datasets/zusmani/petrolgas-prices-worldwide)
- [Scraped extra data for further analysis on Oil production and country populations](https://www.worldometers.info/oil/oil-production-by-country/)
- Program built in PyCharm for scraping data
  - BeautifulSoup & Pandas used
- New data combined with old, then saved as a new CSV [New_Oil_Dataset(20.06.2022).csv](https://github.com/jaffacakes2323/oil_price_scraping/blob/main/New_Oil_Dataset(20.06.2022).csv)

### Data wrangling
- CSV opened in Excel
- New rows with formulas & Flash Fill added for GBP
- Altered some spelling (e.g Liter > Litre) and updated headers with PROPER function
- TRIM function for unwanted spaces
- Format column types (Currency, numeric commas etc.)
- Replaced null values
- Added normalised row (simple feature scaling) for population and yearly oil consumption
- Insert Table & PivotTable (new sheet)
- Added specific columns for PivotTable, and applied some conditional formatting to highlight areas of interest

[Screenshot 1](https://github.com/jaffacakes2323/Portfolio/blob/main/images/oil_pivot.png)
![](https://github.com/jaffacakes2323/Tom_Portfolio/blob/main/images/oil_pivot.png)

### Analysis and Visualisation
- First thing to notice when looking at the PivotTable, is that out of the top 30 of highest oil producing countries, 15 of these are part of the lowest 20% regarding price per litre. Which you would expect from the top producing countries. However, 3 of the top 5 would appear to have a relatively high price in comparison (US, China and Russia). This is likely down to the high consumption per capita and other political influences. 

[Screenshot 2](https://github.com/jaffacakes2323/Tom_Portfolio/blob/main/images/oil_consumption_2.png)
![](https://github.com/jaffacakes2323/Tom_Portfolio/blob/main/images/oil_consumption_2.png)
[Screenshot 3](https://github.com/jaffacakes2323/Tom_Portfolio/blob/main/images/oil_production.png)
![](https://github.com/jaffacakes2323/Tom_Portfolio/blob/main/images/oil_production.png)

- The below pie chart shows that, out of the top 10 oil producing countries, the US, Saudi Arabia and Russia are the biggest contributors by a considerable amount (58% of total top 10 production).

[Screenshot 4](https://github.com/jaffacakes2323/Tom_Portfolio/blob/main/images/oil_production_pie.png)
![](https://github.com/jaffacakes2323/Tom_Portfolio/blob/main/images/oil_production_pie.png)
[Screenshot 5](https://github.com/jaffacakes2323/Tom_Portfolio/blob/main/images/population_oilconsumption.png)
![](https://github.com/jaffacakes2323/Tom_Portfolio/blob/main/images/population_oilconsumption.png)

- Created a column chart to show the top 25 populated countries alongside oil consumption. Again the US stands out here with a much higher consumption rate compared with population. Created a similar column chart whilst filtering by consumption instead, to provide another angle. There are further countries here that show a higher consumption rate in proportion to their population (Japan, Russia, Saudi Arabia, South Korea...). 

[Screenshot 6](https://github.com/jaffacakes2323/Tom_Portfolio/blob/main/images/population_oilconsumption.png)
![](https://github.com/jaffacakes2323/Tom_Portfolio/blob/main/images/population_oilconsumption.png)

The below combo chart helps explore usage per capita further. Unexpectedly, the US is outside of the top 10, despite their much higher net consumption. Singapore is definitely an outlier here, at least doubling all other entries. 7 of these top 10 countries have a much smaller land mass, which is a point of interest and asks for further investigation into why their consumption per capita is so high. Is this politically, economically or culturally influenced?

[Screenshot 7](https://github.com/jaffacakes2323/Tom_Portfolio/blob/main/images/litres_per_capita_by_price.png)
![](https://github.com/jaffacakes2323/Tom_Portfolio/blob/main/images/litres_per_capita_by_price.png)

The final 2 graphs help visualise the countries with the highest and lowest price per litre. North Korea having a 10 times higher price than the average (£1.25 per litre). Clearly a result of heavy sanctions and limited resources.

[Screenshot 8](https://github.com/jaffacakes2323/Tom_Portfolio/blob/main/images/highest_price.png)
![](https://github.com/jaffacakes2323/Tom_Portfolio/blob/main/images/highest_price.png)

Below shows a combo graph for the countries with the lowest price per litre (line) and their production rates, to show if there is a strong correlation with price and production. However, whilst there are some high producing countries here with low prices (Saudi Arabia in particular), there is no clear relationship, as some of the lowest prices also have a low production contribution.

[Screenshot 9](https://github.com/jaffacakes2323/Tom_Portfolio/blob/main/images/lowest_price_production.png)
![](https://github.com/jaffacakes2323/Tom_Portfolio/blob/main/images/lowest_price_production.png)



## [Project 2: IBM Data Analyst Capstone Project](https://github.com/jaffacakes2323/IBM_Capstone)


These are the Notebooks, CSVs, screenshots and links for the [Coursera IBM Data Analyst Capstone project](https://www.coursera.org/professional-certificates/ibm-data-analyst).

Libraries included:

* Pandas
* Beautiful Soup
* JSON
* Requests
* Matplotlib
* Seaborn

[Scraping, API & Exploring](https://github.com/jaffacakes2323/IBM_Capstone/tree/main/Week%201(Scraping%2C%20API%20%26Exploring)) - This folder has 3 notebooks for importing from APIs, web pages, and exploratory analysis: (1) API folder:

- Jobs_API.ipynb (the Flask file used to host API, created by course providers. Everything that follows is my code and work)
- Collecting_Jobs_data_Using_API.ipynb (first assignment for pulling data from API)
- job-postings.xlsx (Excel file created in assignment, after pulling data and sorting into dataframe)

(2) Web scraping folder:

- Web-Scraping-Lab.ipynb (main file for scraping data from website)
- popular-languages.csv (CSV file created after scraping data)

(3) Exploring data folder:

- M1ExploreDataSet-lab.ipynb (main file for exploration)

[Wrangling](https://github.com/jaffacakes2323/IBM_Capstone/tree/main/Week%202(Wrangling)) - This week is for data wrangling (finding, determining, removing duplicates & missing values. Plus normalising data)

- DataWranglingNotebook.ipynb

[Exploratory Analysis](https://github.com/jaffacakes2323/IBM_Capstone/tree/main/Week%203(Exploratory%20DA)) - Further exploratory data analysis (plotting distribution, finding outliers and checking for correlation)

- ExploratoryDataAnalysis.ipynb

[Visualisation & SQLite](https://github.com/jaffacakes2323/IBM_Capstone/tree/main/Week%204(Visualisation)) - Data visualisation (Visualising distribution, relationship, composition and comparison)

- DataVisualisation.ipynb (main folder for assignment)

[Dashboard](https://github.com/jaffacakes2323/IBM_Capstone/tree/main/Week%205(Cognos)) - Using IBM Cognos Analytics to create a dashboard (screenshots included)

- IBM Cloud Pak for data (HTTP link for dashboard)
- survery_data_demographics.csv (data used for dashboard)
- survey_data_technologies_normalised.csv (data used for dashboard)


