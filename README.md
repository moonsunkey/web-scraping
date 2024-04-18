# web-scraping
UCB Challenge #11

# Scrape titles and preview text from Mars news articles.

## Part 1: Scrape Titles and Preview Text from Mars News with the following steps based on the starter code file:

Utilized selenium instead of splinter to automate browsing visiting the Mars news siteLinks to an external site.. Inspect the page to identify which elements to scrape.

Created a Beautiful Soup object to extract text elements from the website.

Extracted the titles and preview text of the scraped news articles.

Stored tored title-and-preview pair in a Python dictionary with title and preview keys. 

Stored and all the dictionaries in a Python lis and printed it in the notebook. I also created a json file as recommended.

# Scrape and analyze Mars weather data, which exists in a table.

## Part 2: Scrape and Analyze Mars Weather Data 

I started off of with the starter code file named part_2_mars_weather.ipynb. 

Used automated browsing to visit the Mars Temperature Data SiteLinks to an external site.. Inspect the page to identify which elements to scrape. 

Created a Beautiful Soup object and use it to scrape the data in the HTML table.

Assemble the scraped data into a Pandas DataFrame with the column headings of id, terrestrial_date, sol, ls, month, min_temp and pressure.

The below questions are answered using Pandas functions:

How many months exist on Mars?
How many Martian (and not Earth) days worth of data exist in the scraped dataset?
What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question: Find the average minimum daily temperature for all of the months. Plot the results as a bar chart.
![Example Image](./images/Average_temp_per_month_sorted.png)

Which months have the lowest and the highest atmospheric pressure on Mars? I charted the average daily atmospheric pressure of all the months. The barchart is shown below:
![Example Image](./images/Average_Pressure_by_Month.png)

About how many terrestrial (Earth) days exist in a Martian year? I plotted the daily minimum temprature and visually estimated from peak to peak. The chart is shown below: 
![Example Image](./images/Temp_by_Terrestrial_Days.png)

Lastly, I exported the DataFrame to a CSV file.

All images are saved in the Images folder and the CSV file is saved in the Output folder.






Web Scraping Mars Data
Overview
This project involves web scraping to collect Mars-related data from various websites. The data includes news articles, weather reports, and temperature data, which are processed and analyzed using Python libraries such as Selenium and BeautifulSoup. Results are visualized and stored in JSON and CSV formats.

Challenge Details
UCB Challenge #11
Part 1: Scrape Titles and Preview Text from Mars News
Objective: Automate the browser to visit the Mars news site and scrape titles and preview texts.

Steps:

Automation Setup: Utilize Selenium for browser automation to access the Mars news site.
Data Extraction: Use BeautifulSoup to parse the webpage and extract titles and preview texts.
Data Storage:
Store each title and preview text in a dictionary with keys title and preview.
Aggregate all dictionaries into a list and print the results in the notebook.
Output the data into a JSON file as recommended.
Part 2: Scrape and Analyze Mars Weather Data
Objective: Analyze Mars weather data collected from an HTML table on the Mars Temperature Data Site.

Steps:

Web Scraping:
Use automated browsing to visit the Mars Temperature Data Site.
Inspect the page elements to determine the necessary data points.
Scrape the data using BeautifulSoup and store it in a Pandas DataFrame with appropriate column headings.
Data Analysis:
Answer key questions about Martian weather using Pandas:
How many months exist on Mars?
How many Martian days' worth of data are in the dataset?
Identify the coldest and warmest months on Mars by calculating the average minimum daily temperature and visualizing it with a bar chart.
Determine which months have the lowest and highest atmospheric pressure and visualize the results.
Exporting Data:
Export the final DataFrame to a CSV file.
Visualizations:

Average Temperature by Month:
Average Temperature per Month
Average Atmospheric Pressure by Month:
Average Pressure by Month
Temperature by Terrestrial Days:
Temperature by Terrestrial Days
File Organization:

All images are stored in the Images folder.
The output CSV file is stored in the Output folder.