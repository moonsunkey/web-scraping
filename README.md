# web-scraping
UCB Challenge #11


# Scrape titles and preview text from Mars news articles.

## Part 1: Scrape Titles and Preview Text from Mars News with the following steps:

Utilized selenium instead of splinter to automate browsing visiting the Mars news siteLinks to an external site.. Inspect the page to identify which elements to scrape.

Created a Beautiful Soup object to extract text elements from the website.

Extracted the titles and preview text of the scraped news articles.

Stored tored title-and-preview pair in a Python dictionary with title and preview keys. 

Stored and all the dictionaries in a Python lis and printed it in the notebook.

# Scrape and analyze Mars weather data, which exists in a table.

## Part 2: Scrape and Analyze Mars Weather Data

Open the Jupyter Notebook in the starter code folder named part_2_mars_weather.ipynb. You will work in this code as you follow the steps below to scrape and analyze Mars weather data.

Use automated browsing to visit the Mars Temperature Data SiteLinks to an external site.. Inspect the page to identify which elements to scrape. Note that the URL is https://static.bc-edx.com/data/web/mars_facts/temperature.html.

HINT
Create a Beautiful Soup object and use it to scrape the data in the HTML table. Note that this can also be achieved by using the Pandas read_html function. However, use Beautiful Soup here to continue sharpening your web scraping skills.

Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website. Here’s an explanation of the column headings:

id: the identification number of a single transmission from the Curiosity rover
terrestrial_date: the date on Earth
sol: the number of elapsed sols (Martian days) since Curiosity landed on Mars
ls: the solar longitude
month: the Martian month
min_temp: the minimum temperature, in Celsius, of a single Martian day (sol)
pressure: The atmospheric pressure at Curiosity's location
Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.

HINT
Analyze your dataset by using Pandas functions to answer the following questions:

How many months exist on Mars?
How many Martian (and not Earth) days worth of data exist in the scraped dataset?
What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
Find the average minimum daily temperature for all of the months.
Plot the results as a bar chart.
Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
Find the average daily atmospheric pressure of all the months.
Plot the results as a bar chart.
About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
Consider how many days elapse on Earth in the time that Mars circles the Sun once.
Visually estimate the result by plotting the daily minimum temperature.
Export the DataFrame to a CSV file.

