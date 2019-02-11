# LOVScraper

## Description
Script in python made to scrape Linked Open Vocabularies to get:
 - all the vocabulary's .n3 files (all of which saved in the directory vocabs/)
 - other metadata information about the vocabularies (saved in LOV.xlsx in various sheets)
 
## How to use
First of all we need to install python and pip
Then we need to install a few libraries, such as:
 - time
 - json
 - re
 - requests
 - urllib
 - beautifulsoup4
 - xlsxwriter
 - xlrd
 - pandas
 
 ## Results
 In the end, just executing LOVScraper.py and letting it run for about half an hour, we will get: 
 - a folder named vocabs/ with inside all the available vocabularies of LOV
 - a file LOV.xlsx with all the metadata information obtained from all the scraped vocabularies' pages
 - a file log.txt with information about what has gone wrong scraping LOV (missing .n3 file or bad links to .n3 files)
