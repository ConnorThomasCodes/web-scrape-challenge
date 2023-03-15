# web-scrape-challenge

In this repository we use a chrome driver to access various webpages (<https://static.bc-edx.com/data/web/mars_news/index.html> and <https://static.bc-edx.com/data/web/mars_facts/temperature.html> and then a BeautifulSoup html parser to read and analyze some of the information we receive from each of the sites.

In the part_1 notebook, we go through the posted news articles and grab each title and article preview to add to a list.

In the part_2 notebook, we copy a table of Mars temperature data into a pandas dataframe for some further analysis and visualization on the recorded mars temperatures and pressures in our dataset. We end by doing a visual estimation of the length of a Martian year by doing a peak-to-peak (and valley-to-valley) analysis on our temperature data, with the assumption that peaks in temperatures will represent the equivalent period consecutive Mars years (Mars summer to the next Mars summer).

The dataframe from part_2 is also exported as mars_temps.csv for easy access.
