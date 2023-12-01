# datacoll-challenge
Module 11 Challenge


## Description 
**datacoll-challenge** solution, due 12/05/2023


## Requirements 

### Part 1: Scrape Titles and Preview Text from Mars News (40 points)
- [X] Automated browsing (with Splinter) was used to visit the Mars news site, and the HTML code was extracted (with Beautiful Soup). (10 points)
- [X] The titles and preview text of the news articles were scraped and extracted. (20 points)
- [X] The scraped information was stored in the specified Python data structure —specifically, a list of dictionaries. (10 points)

### Part 2: Scrape and Analyze Mars Weather Data (60 points)
- [X] The HTML table was extracted into a Pandas DataFrame. Either Pandas or Splinter and Beautiful Soup were used to scrape the data. The columns have the correct headings and data types. (15 points)
- [X] The data was analyzed to answer the following questions: (10 points)
* How many months exist on Mars? (5 points)
* How many Martian days' worth of data are there? (5 points)
- [X] The data was analyzed to answer the following questions, and a data visualization was created to support each answer: (30 points)
* Which month, on average, has the lowest temperature? The highest? (10 points)
* Which month, on average, has the lowest atmospheric pressure? The highest? (10 points)
* How many terrestrial days exist in a Martian year? A visual estimate within 25% was made. (10 points)
- [X] The DataFrame was exported into a CSV file. (5 points)


## Submission
* Deliverable 1: A Jupyter notebook containing code that scrapes the Mars news titles and preview text; filename _part_1_mars_news_solution.ipynb_
* Additionally a JSON file containing the scraped data; filename _title_preview.json_
* Deliverable 2: A Jupyter notebook containing code that scrapes the Mars weather data and that cleans, visualizes, and analyzes that data; filename _part_2_mars_weather_solution.ipynb_
* Additionally a CSV file containing  the scraped data; filename _weather.csv_


## Credits 
* Used stackoverflow, Beautiful Soup, JSON and Python documentation for specific details
