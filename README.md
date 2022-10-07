# DATA 512 HW 1

## Goal

The goal of this assignment is to acquire page view data on dinosaur articles from Wikipedia to draw insights such as which articles have the most or least views in a given time period.

## About the Data

Wikimedia API: https://www.mediawiki.org/wiki/REST_API  
Content retrieved from the API is licesnsed under the CC-BY-SA 3.0 and GFDL licenses.  
Terms and Conditions of use: https://www.mediawiki.org/wiki/REST_API#Terms_and_conditions

The pulled data ranges from July 2015 to the end of September 2022. 
There are months with no data for the page views for certain months that were left as null values and this was done on purpose to differentiate from when the API specifies that the view count is 0.

The output consists of 3 JSON files for monthly mobile views, monthly desktop views, and monthly cumulative views. The main variables of interests are the dinosaur names, date (YYYYMM), and page views. These files can be found in ```raw_data```.

## Project Structure

```
└── data-512-homework_1
    ├── LICENSE
    ├── README.md
    ├── raw_data
    │   ├── dino_monthly_cumulative_201507-202210.json
    │   ├── dino_monthly_desktop_201507-202210.json
    │   ├── dino_monthly_mobile_201507-202210.json
    │   └── dino_clean.csv
    ├── graphs
    │   ├── top10_fewest.png
    │   ├── max_min_avg.png
    │   └── top_10_pages.png
    └── src
        ├── data_acquisition_and_analysis.ipynb
```


