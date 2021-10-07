# DATA 512: Assignment 1 - Data Curation

## Goal
The goal of this assignment is to perform a data curation on to analyze English Wikipedia from 2008 to 2021. The results from implementing this project is that it can be fully reproduced by any user trying to perform a similar analysis

## Data Source and Description
The data used for this assignment are from two APIs: 
1. The Legacy Pagecounts API:
    * Documentation: https://wikitech.wikimedia.org/wiki/Analytics/AQS/Legacy_Pagecounts
    * REST API: https://wikimedia.org/api/rest_v1/#/Legacy%20data
2. The Pageviews API
    * Documentation: https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews
    * REST API: https://wikimedia.org/api/rest_v1/#/Pageviews%20data

The data collected from these two sources were combined into a final .csv file: en-wikipedia_traffic_200712-202108.csv and it has the following columns: 
['year', 'month', 'pagecount_all_views', 'pagecount_desktop_views',
 'pagecount_mobile_views', 'pageview_all_views',
 'pageview_desktop_views', 'pageview_mobile_views']


## Analysis Result

![alt text](https://github.com/HasnahSaid/data-512-a1/blob/main/wiki_traffic_2008_2021.png)

## License and Terms of Use 

Wikimedia Terms of Use: https://foundation.wikimedia.org/wiki/Terms_of_Use/en

Repository License: MIT License