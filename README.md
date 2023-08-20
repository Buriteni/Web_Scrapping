# Web_Scrapping
#### Deliverable 1: Scrape Titles and Preview Text from Mars News
In the first data set I scraped web data from Mars News website to gather information about the website itself. By scraping this data, I can gain insight into how to gather the title data, preview text and articles.   In order to effectively scrape the website, it is important to identify which elements of the site were relevant and useful. This included looking at text content such as headlines, and summaries that are featured on the site. After identifying these elements, I used Python programming language with Beautiful Soup library in order to extract them from HTML code I wanted to scrap. This was the start of gathering any further data needed to research this site. 

#### Deliverable 2: Scrape and Analyze Mars Weather Data
The website contains data on the temperature and atmospheric pressure of Mars, measured by the Curiosity rover over a period of one Martian year (687 Earth days). The data is presented in a table and some charts that show the trends and patterns of the Martian climate.
To store the data, I assemble the scraped data into a Pandas DataFrame. I used Python, pandas, and Beautiful soup to loop through the data and create a list of rows that create a data frame that contains the columns for the table id, terrestrial_date, sol, ls, month, min_temp, pressure. 
To prepare the data for analysis, I checked for any missing or invalid values and replaced them with appropriate values. I had some hiccups along the way, but I was able to update the data types for analysis, by converting to astype.  
To analyze the data using charts, I used Python and matplotlib to create various types of plots that show the relationship between different variables. For example, I created a bar plot that shows how the minimum and maximum temperature vary over the Martian year. I also created a line plot that shows how many terrestrial days there are in a Martian year. I used the plt.plot, plt.bar, plt.xlabel, plt.ylabel, plt.title, and plt.show functions in matplotlib to create these plots.
To save the data, I exported the data frame as a new CSV file with the converted units and saved it in my local directory.

#### Resourses
AskBCS, 
Tutors, 
https://pandas.pydata.org/docs/reference/api/pandas.Series.to_csv.html,
Previous assignments,
https://stackoverflow.com/,
https://www.crummy.com/software/BeautifulSoup/bs4/doc/