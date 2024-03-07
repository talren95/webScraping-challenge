## Repository Structure:
In the repository provided, you can locate the Jupyter notebooks under the "Notebooks" folder. After running all the cells in the second notebook (part_2_mars_weather.ipynb), a CSV file will be generated outside of the "Notebooks" directory, containing all the scraped information from the mars website.

## Part 1: Scrape Titles and Preview Text from Mars News:
Inspect the Mars news website to identify elements to scrape.
Use Beautiful Soup to create a parser and extract text elements from the website.
Extract titles and preview text of news articles and store them in Python dictionaries.
Store all dictionaries in a Python list and optionally export the scraped data to a JSON file.

## Part 2: Scrape and Analyze Mars Weather Data:
Visit the Mars Temperature Data Site and identify elements to scrape.
Use Beautiful Soup to scrape data from the HTML table.
Assemble the scraped data into a Pandas DataFrame with specific column headings.
Examine the data types and convert them to appropriate types if necessary.
Analyze the dataset using Pandas functions to answer several questions, such as:
Number of months on Mars
Number of Martian days worth of data in the dataset
Coldest and warmest months on Mars based on minimum daily temperature
Months with lowest and highest atmospheric pressure on Mars
Approximate number of terrestrial days in a Martian year
Visualize the results using bar charts and plot daily minimum temperature to estimate the number of terrestrial days in a Martian year.
Export the DataFrame to a CSV file.

## In summary:
The analysis involves scraping Mars news articles and weather data, organizing and analyzing the scraped data, and visually communicating insights through charts. This project was an engaging and enjoyable challenge, offering an opportunity to delve into web scraping techniques. I found both parts of the analysis, scraping Mars news articles and weather data, to be rewarding exercises in applying my skills. Not only did this challenge strengthened my web scraping abilities but also provided insights into organizing and analyzing data, which I find immensely valuable.
