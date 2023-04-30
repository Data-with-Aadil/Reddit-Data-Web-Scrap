# Reddit Posts-Data Scrapping

This Python script scrapes data from Reddit posts using the requests library, BeautifulSoup, pandas, and openpyxl. The script scrapes the data from a given list of Reddit user profile links, gets all the unique post links from those user profiles, and saves the scraped data to a CSV file.

## Requirements
- Python 3.x
- requests library
- BeautifulSoup library
- pandas library
- openpyxl library

## How to Use
1. Set the `reddit_links_to_be_tracked` variable to a list of Reddit user profile links.Always add the link starting with 'old.' inplace of 'www.'
2. Run the script.
3. The script will output a CSV file named "reddit_data.csv" in the current working directory.

## Functionality
1. The script scrapes all the unique post links from the given Reddit user profiles.
2. The script then iterates through each post link, extracts the relevant data from the JSON response, and saves it to a pandas DataFrame.
3. The pandas DataFrame is then written to a CSV file.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
