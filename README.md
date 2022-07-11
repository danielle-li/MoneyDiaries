# Avocado spending by millennials

This folder provides supporting data and code for an analysis of spending on avocados and avocado toast, available [here](https://danielle-li.github.io/money-diaries/).  This analysis was done as part of a project for the [Lede Program in Data Journalism](https://ledeprogram.com/) at Columbia University.  

## Data Sources

The data were scraped from Refinery29's Money Diaries.  

## Analysis

Analysis was done with Python and visualization was done with Datawrapper and Adobe Illustrator.  

## Repository contents

#### Code
- [step1_scrape_money_diaries.ipynb](./Code/step1_scrape_money_diaries.ipynb).  Located in the Code folder.  Scrapes text and comments (comment scraping fails a lot) using bs4 and selenium.
- [step2_data_analysis.ipynb](./Code/step2_data_analysis.ipynb).  Located in the Code folder.  Takes the output of the scraping and conducts analysis.  

#### Working Data
- [moneydiaries_nocomments.csv](./InputData/moneydiaries_nocomments.csv) This is the file used for the analysis.  There are a couple other files in the folder, but they contain errors and have not been cleaned.  

#### Final Data
- [avo_bysal.csv](./FinalData/avo_bysal.csv) and [avo_bydebttosal.csv](./FinalData/df_chart_norating_clean.csv). Data on avocado consumption by salary and debt to salary ratios, respectively.  

#### Input Figures 
- Various pngs of avocados.  






