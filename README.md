# Tom_Portfolio

Data Analysis


## [Project 1: June 2022 Oil Price Analysis](https://github.com/jaffacakes2323/oil_price_scraping)

### Collecting Data
- [Downloaded data from Kaggle for analysis](https://www.kaggle.com/datasets/zusmani/petrolgas-prices-worldwide)
- [Scraped extra for further anaylsis on Oil production and country populations](https://www.worldometers.info/oil/oil-production-by-country/)
- Program built in PyCharm for scraping population and oil production data
  - BeautifulSoup & Pandas used
- New data combined with old, then saved as a new CSV [New_Oil_Dataset(20.06.2022).csv](https://github.com/jaffacakes2323/oil_price_scraping/blob/main/New_Oil_Dataset(20.06.2022).csv)

### Data wrangling
- CSV opened in Excel
- Most data had already been cleaned
- New rows with formulas & Flash Fill added for GBP
- Altered some spelling (e.g Liter > Litre) and udpated headers with PROPER function
- TRIM function for unwanted spaces
- Format column types (Currency, numeric commas etc.)
- Replace null values
- Added normalised row (simple feature scaling) for population and yearly oil consumption
- Insert Table & PivotTable (new sheet)
- Added specific columnns for PivotTable, and applied some conditional formatting to highlight areas of interest. Some countries with particularly high & low Price per litre stood out
![](https://github.com/jaffacakes2323/Tom_Portfolio/blob/main/images/oil_pivot.png)

### Analysis and Visualisation
- First thing to notice when looking at the PivotTable, is that in the top 30 of highest oil producing countries, 15 of these are part of the lowest 20% regarding price per litre. Which you would except from the top oil producing countries. 3 of the top 5 would appear to have a relatively high price in comparison (US, China and Russia). This is likely down to the high consumption per capita and other political influences. 

![Screenshot 1](https://github.com/jaffacakes2323/Tom_Portfolio/blob/main/images/oil_consumption_2.png)
![Screenshot 2](https://github.com/jaffacakes2323/Tom_Portfolio/blob/main/images/oil_production.png)

The below pie chart shows that, out of the top 10 oil producing countries, the US, Saudia Arabia and Russia are the biggest contirbutors by a considerable amount (58% of total top 10 production).
![Screenshot 3](https://github.com/jaffacakes2323/Tom_Portfolio/blob/main/images/oil_production_pie.png)
