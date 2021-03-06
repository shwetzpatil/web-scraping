# Web-Scraping
---
Web Scraping from website WeGotTickets.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

## Intended Functionality
Our objective is to scrape the following data from from http://www.wegottickets.com/:
 * the artists playing
 * the city
 * the name of the venue
 * the date
 * the price and stored in a CSV file.

## Pre-requisites
1. Ruby v2.5.0
1. bundle (v1.16.1)
2. RSpec (v3.7)

## Packages used
1. HTTParty (to get the HTML pages)
2. Nokogiri (to parse the HTML pages)
3. Pry (to help with debugging)

## Installation steps
1. Clone this repository
1. Go to the root directory
2. Run the command `bundle install` to install required dependencies

## Run the code
1. To run the code, run the command `ruby src/wegottickets_scraper.rb` in the root directory.
2. The results should appear in `src/result.csv`. To modify this code, you can change the last line in `src/wegottickets_scraper.rb` (line 99) to specify the path to the output file and also how many pages you want to scrape.

## Running the tests
Run the the command `rspec` in the root directory.

## Bugs/issues
if you find any bugs or issues file it here `https://github.com/shwetzpatil/web-scraping/issues`.