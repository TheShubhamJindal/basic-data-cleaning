# basic-data-cleaning
Pull the data from Wikipedia, using the request library. 
The link for the data : https://en.wikipedia.org/wiki/List_of_countries_by_GDP_(nominal)_per_capita

Using BeautifulSoup, parse the obtained DOM and make it into a Pandas dataframe. 

After that, clean the the obtained dataframe by removing the 'Rank' column, since it has corrupted rows (rows with a - in them, intead of an integer). 
Change the type of the data in the gdp column, so that the numerical computing functions provided by Pandas can be used, since they do not work on strings. 
