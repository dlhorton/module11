# Mars Weather Data Analysis

This project involves scraping and analyzing Mars weather data from various sources. The project consists of two parts:

1. **Scraping Titles and Preview Text from Mars News**
   - This part involves scraping titles and preview text from the Mars news website.
   - The data is scraped using automated browsing with Splinter and HTML parsing with Beautiful Soup.
   - The scraped data is stored in a Python list and optionally exported to a JSON file.

2. **Scraping and Analyzing Mars Weather Data**
   - This part involves scraping and analyzing Mars weather data from a webpage.
   - The data includes information such as the identification number of transmissions from the Curiosity rover, terrestrial date, Martian sols (days), solar longitude, Martian months, minimum temperature, and atmospheric pressure.
   - The data is scraped using Beautiful Soup and assembled into a Pandas DataFrame.
   - Data types are adjusted as needed for analysis.
   - Various questions about the data are answered, including the number of months on Mars, the number of Martian days' worth of data, average low temperature by month, coldest and hottest months, average pressure by Martian month, and the approximate number of terrestrial days in a Martian year.
   - Visualizations, such as bar charts, are created to illustrate the analysis results.

## Files Included:
- `part_1_mars_news.ipynb`: Jupyter Notebook for scraping titles and preview text from Mars news.
- `part_2_mars_weather.ipynb`: Jupyter Notebook for scraping and analyzing Mars weather data.
- `mars_weather_data.csv`: CSV file containing the scraped Mars weather data.

## Dependencies:
- Python 3.x
- Libraries: requests, BeautifulSoup, pandas, matplotlib

