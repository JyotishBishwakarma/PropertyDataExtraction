# Palm Beach County Property Data Scraper

## Overview
Welcome to the Palm Beach County Property Data Scraper project! This tool allows you to efficiently extract valuable property data from the Palm Beach County Property Appraiser's website. By automating the process of searching, navigating through results, and scraping relevant details, this project saves time and effort for anyone looking to analyze or use property data in Palm Beach County, Florida.

## Features
* Web Scraping: Utilizes web scraping techniques to gather property data from the Palm Beach County Property Appraiser's website.
* Search and Navigation: Conducts searches based on user-defined criteria and navigates through the search results to access detailed property information.
* Data Cleaning: Implements data cleaning procedures to ensure extracted information is accurate and ready for analysis

## Tech Stacks
* Selenium
* Beautiful Soup
* Pandas

## Project Details
The script here goes to advanced search page: https://www.pbcgov.org/papa/Asps/GeneralAdvSrch/SearchPage.aspx?f=a where it searches by 334 which is starting characters for all palm Beach County. It gives the result where the proerties are listed. There are around 1 million records paginated to 1000s of pages and then we need to click each record and get the below data and generate a csv file.

Following information was captured:
ParcelId| Owner Name| Property Address| CITY| County| Zipcode| State| Property Value| Land Use

## Acknowledgments
Special thanks to the Palm Beach County Property Appraiser's website for providing valuable property information.
Feel free to use, modify, and improve this project to meet your specific needs!




