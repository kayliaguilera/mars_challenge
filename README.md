# mars_challenge
Deliverable 1: Scrape Titles and Preview Text from Mars News
Open the Jupyter Notebook in the starter code folder named part_1_mars_news.ipynb. You will work in this code as you follow the steps below to scrape the Mars News website.

Use automated browsing to visit the Mars NASA news site Links to an external site.. Inspect the page to identify which elements to scrape.
Create a Beautiful Soup object and use it to extract text elements from the website.

Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures as follows:

Store each title-and-preview pair in a Python dictionary. And, give each dictionary two keys: title and preview. An example is the following:
Store all the dictionaries in a Python list.

Print the list in your notebook.

Optionally, store the scraped data in a file or database (to ease sharing the data with others). To do so, export the scraped data to either a JSON file or a MongoDB database.

Deliverable 2: Scrape and Analyze Mars Weather Data
Open the Jupyter Notebook in the starter code folder named part_2_mars_weather.ipynb. You will work in this code as you follow the steps below to scrape and analyze Mars weather data.

Use automated browsing to visit the Mars Temperature Data Site Links to an external site.. Inspect the page to identify which elements to scrape. Note that the URL is https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html.

Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website. Here’s an explanation of the column headings:

id: the identification number of a single transmission from the Curiosity rover
terrestrial_date: the date on Earth
sol: the number of elapsed sols (Martian days) since Curiosity landed on Mars
ls: the solar longitude
month: the Martian month
min_temp: the minimum temperature, in Celsius, of a single Martian day (sol)
pressure: The atmospheric pressure at Curiosity's location
Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.

Requirements
Deliverable 1: Scrape Titles and Preview Text from Mars News (40 points)
Automated browsing (with Splinter) was used to visit the Mars news site, and the HTML code was extracted (with Beautiful Soup) (10 points)

The titles and preview text of the news articles were scraped and extracted (20 points)

The scraped information was stored in the specified Python data structure—specifically, a list of dictionaries (10 points)

Deliverable 2: Scrape and Analyze Mars Weather Data (60 points)
The HTML table was extracted into a Pandas DataFrame. Splinter and Beautiful Soup were used to scrape the data. The columns have the correct headings and data types (15 points)

The data was analyzed to answer all five listed questions, with data visualizations provided when specified (40 points)

The DataFrame was exported into a CSV file (5 points)
