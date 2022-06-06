# MLS_Scrape
## Overview
Zillow tends to have older listings, thus in a competitive market like Colorado, its hard for clients to be up to date. The goal is to create an app for realtors that automates scraping MLS info, filters based on clients specifications and returns a map of their potential houses.
### Purpose
Use Selenium to automate web browsing tasks in conjuction with pandas random for randomizing user 'activity.' Then convert desired table to a soup object and store its data in a pandas dataframe. Finally call google maps API to get their [lat, lng] coordinates and plot them with key information labeled.
## Scrape
### Selenium Login 
https://user-images.githubusercontent.com/79609464/171085248-05508a48-80b2-4842-9334-1ec9e3446bbf.mp4

### Beautiful Soup Scrape
https://user-images.githubusercontent.com/79609464/171085521-64f2a9eb-eea8-4ef9-a20c-51642d2b1d70.mp4

### Google Maps Vizualization
https://user-images.githubusercontent.com/79609464/171085723-d7660a70-9da4-40d2-9520-d7c04570107a.mp4

## Summary
We've created an app that uses python to scrape data, store it in a dataframe, cross references google maps API, then plots the coordinate. To further improve this project we can create a webapplication to run an exported version of scraping.py and display its data. 
