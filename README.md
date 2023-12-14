# Mars Exploration Data Analysis Project

## Overview

This project focuses on web scraping and data analysis related to Mars exploration. It consists of two main deliverables: extracting news article information and analyzing Mars weather data.

## Deliverables

### Deliverable 1: Mars News Article Scraping
- **Objective:** Scrape titles and preview texts from Mars news articles.
- **Method:** Utilized Splinter and BeautifulSoup to extract article titles and previews from a given Mars news website.
- **Outcome:** Compiled a structured dataset containing the titles and preview texts of various Mars-related news articles.

### Deliverable 2: Mars Weather Data Analysis
- **Objective:** Scrape and analyze data from a Mars weather data table.
- **Data Collection:** Extracted Mars weather data including terrestrial dates, Martian sols, temperatures, and atmospheric pressures using web scraping.
- **Data Analysis:**
  1. Processed and analyzed the data using a Pandas DataFrame.
  2. Calculated key measures such as: unique Martian months, average low temperatures, and atmospheric pressures.
  3. Identified the coldest and warmest Martian months based on average temperatures.
  4. Estimated the length of a Martian year in Earth days through visual analysis of temperature patterns.
  5. Visualized temperature and pressure data using bar charts.

### Data Export
Exported the final dataset to a CSV file for external use or further analysis.

## Tools Used
- Python Libraries: Pandas, BeautifulSoup, Splinter, Matplotlib
