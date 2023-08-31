# Web-Scraping-Challenge

## Overview:
In this assignment, we were to utilize two starter codes to properly scrape through and analyze news regarding Mars, and the weather patterns of Mars. Throughout the assignment, we were tasked with analyzing certain segments of each webpage, and properly graphing said segments to compare to Earth. Once the analysis was complete, our output was written to a CSV file which is included in this repository under the Output folder. 

## Deliverable 1: Scrape Title and preview text from Mars News Articles. 

- Used automated browsing to visit Mars News site. Utilized ChromeDev Tools to properly identify which segments to narrow code down to. 
- Created a Beautiful Soup object and extracted all text elements within website. 
- Extracted titles and previews of article information and placed them into a list of dictionaries. 
- Finally, printed out the list of all titles and previews. Then quit out of the browser. 

## Deliverable 2: Scape and analyze Mars Weather data.

- Used automated browsing to visit Mars Temperature Data site, and followed same steps as above to identify elements needed to scrape.
- Created Beautiful soup object. 
- Put scraped data into a Pandas DataFrame, and made sure column headings are the same as the table on the website. 
- Examined the data types and made sure to change the necessary types for a few columns. 
- Analyzed the dataset to answer the following questions: 
    How many months exist on Mars?
    How many Martian (and not Earth) days worth of data exist in the scraped dataset?
    What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
        Find the average minimum daily temperature for all of the months.
        Plot the results as a bar chart.
    Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
        Find the average daily atmospheric pressure of all the months.
        Plot the results as a bar chart.
    About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
        Consider how many days elapse on Earth in the time that Mars circles the Sun once.
        Visually estimate the result by plotting the daily minimum temperature.
- Exported Dataframe to CSV file that is saved under Output folder. 

Starter code was provided by UO Data Analytics Bootcamp. Used that with the in-class activities to properly develop and execute code. 
