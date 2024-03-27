# 🏘 Housing prices forecast -- UK 🇬🇧 (southeast) [updating daily!]
```
Forecasting housing prices in the UK South Eastern Area using the data scraped from Savills
```
## 🖼️ A small background of this project
My family has recently moved to the UK and is currently looking at houses in the Southeast. It's been a bit of a  struggle like it is for everyone

when making a big purchase. So, I've decided to do some extra research on the area we're interested in. By collecting additional information 

and gaining a broader perspective, I aim for us to reach a data-driven conclusion.

## 👨🏻‍💻 Where do I get these data & How do I deal with them
Scraping Housing Data [webscraper.io](https://webscraper.io/): This enabled me to conveniently gather different pieces of information from each listing using a point-

and-click interface. The 113 properties' data was scraped from Savills -- the most informative real estate website I've found online (for the UK 

area).


Go ahead & take a look at [this](https://webscraper.io/tutorials) link if you want to scrape data from the other websites. Web scraping is performed by powerful software which 

can put a heavy load on website servers. You should make sure that you achieve the optimal rate of the web scraping process so the bandwidth 

and performance of the web server will not not affected -- Happy Scraping & Scrape ethically! :)


By the way, the scraped data is shown in the `housing_data` folder, feel free to check them out if you're curious about the format.  

## Installation guide
Python, Jupyter Notebook, and -pip install every toolkit mentioned in the notebook are everything you need. Download the `SE_housing.ipynb` 

file and all the .csv files in the `housing_data` file and run them in the notebook. Here are the libraries used: 
a. Pandas

b. Scikit Learn

c. Numpy

d. Seaborn

e. Matpoltlib

f. Datetime

g. Geopy

h. Scipy

i. Plotly.express

## Exploratory Data Analysis (EDA)
The following show the statistics and the distributions of housing prices in the Southeast area

Visualization of housing price distribution: Most of our properties lie between the price range of 0.5 - 2.25 MM pounds.
![](output_charts/distribution_chart.png)

![](output_charts/price_des.png)

