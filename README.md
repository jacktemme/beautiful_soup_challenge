Module 11

This repository contains two Juptyer Notebook files, where the python library Beautiful Soup was used to scrape specific info from the html of two websites. The part_1_mars_news file scrapes the title and preview of mars news articles and stores them as a a list of dictionaries. In part_2_mars_weather a data table on attributes of mars' weather is scraped from a website and then turned into a pandas data frame in order to perform analysis. From here data is cleaned and sorted and the temperature and pressure changes on mars are visualized through the matplot library. The temperature on mars vs days on earth is also plotted in order to give an estimate on the number of earth days that equate to a year on mars. This dataframe was exported to the mars.csv that can be found in the data folder.

Chat GPT was utilized to help with plotting the number of days on earth with the utilization of the np.arange function.

days = np.arange((end_date - start_date).days + 1)

The websites used were:

https://static.bc-edx.com/data/web/mars_news/index.html

https://static.bc-edx.com/data/web/mars_facts/temperature.html
