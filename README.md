# Web Scraping Mars Data

## Overview

This project involves web scraping to collect Mars-related data from various websites. The data includes news articles, weather reports, and temperature data, which are processed and analyzed using Python libraries such as Selenium and BeautifulSoup. Results are visualized and stored in JSON and CSV formats.

## Challenge Details

### UCB Challenge #11

#### Part 1: Scrape Titles and Preview Text from Mars News

**Objective**: Automate the browser to visit the Mars news site and scrape titles and preview texts.

**Steps**:

1. **Automation Setup**: Utilize Selenium for browser automation to access the Mars news site.
2. **Data Extraction**: Use BeautifulSoup to parse the webpage and extract titles and preview texts.
3. **Data Storage**:
   - Store each title and preview text in a dictionary with keys `title` and `preview`.
   - Aggregate all dictionaries into a list and print the results in the notebook.
   - Output the data into a JSON file as recommended.

#### Part 2: Scrape and Analyze Mars Weather Data

**Objective**: Analyze Mars weather data collected from an HTML table on the Mars Temperature Data Site.

**Steps**:

1. **Web Scraping**:
   - Use automated browsing to visit the Mars Temperature Data Site.
   - Inspect the page elements to determine the necessary data points.
   - Scrape the data using BeautifulSoup and store it in a Pandas DataFrame with appropriate column headings.
2. **Data Analysis**:
   - Answer key questions about Martian weather using Pandas:
     - How many months exist on Mars?
     - How many Martian days' worth of data are in the dataset?
     - Identify the coldest and warmest months on Mars by calculating the average minimum daily temperature and visualizing it with a bar chart.
     - Determine which months have the lowest and highest atmospheric pressure and visualize the results.
3. **Exporting Data**:
   - Export the final DataFrame to a CSV file.

**Visualizations**:

- **Average Temperature by Month**: 
  ![Average Temperature per Month](./images/Average_temp_per_month_sorted.png)
- **Average Atmospheric Pressure by Month**: 
  ![Average Pressure by Month](./images/Average_Pressure_by_Month.png)
- **Temperature by Terrestrial Days**: 
  ![Temperature by Terrestrial Days](./images/Temp_by_Terrestrial_Days.png)

**File Organization**:

- All images are stored in the `Images` folder.
- The output CSV file is stored in the `Output` folder.
