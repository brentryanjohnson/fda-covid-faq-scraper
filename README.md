# FDA COVID-19 FAQ web scraper

This is a basic web scraper for [Food and Drug Administration (FDA) frequently asked questions page](https://www.fda.gov/emergency-preparedness-and-response/coronavirus-disease-2019-covid-19/coronavirus-disease-2019-covid-19-frequently-asked-questions) related to the COVID-19 pandemic.

The scraper outputs a CSV file with the questions and answers in separate columns.

## Dependencies
- python
- pandas
- requests
- beautiful soup (bs4)
- time
- unicodedata

## Enhancements needed
Relative links have not yet been converted to absolute links in the output CSV. The relative links will be broken until the script converts them to absolute links. 
