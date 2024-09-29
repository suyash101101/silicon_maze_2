## Screener.in Web Scraper
This project contains three Python scripts for scraping financial data from Screener.in. Each script focuses on different aspects of company data, presented with a Pokemon-themed twist.
Scripts

basic_pokemon_stats.py (Code 1)

Scrapes basic financial information from the balance sheet.
Outputs: Basic_Pokemon_Stats.csv


pokemon_item_inventory.py (Code 2)

Extracts detailed balance sheet data.
Outputs: Pokemon_Item_Inventory.csv


battle_performance_stats.py (Code 3)

Collects profit and loss data along with key ratios for the last three years.
Outputs: Battle_Performance_Stats.csv



## Dependencies

Python 3.x
requests
beautifulsoup4
csv (built-in)

## Setup

Install the required packages:
Copypip install requests beautifulsoup4

Ensure you have write permissions in the directory where the scripts are located.

 ## Usage
Run each script individually:
Copypython basic_pokemon_stats.py
python pokemon_item_inventory.py
python battle_performance_stats.py
Each script will generate a CSV file in the specified location (currently set to /Users/suyashnahar/Desktop/).
Data Collected

Basic_Pokemon_Stats.csv: Reserves, Borrowings, Total Liabilities, Fixed Assets, Investments, Total Assets
Pokemon_Item_Inventory.csv: Same as Basic_Pokemon_Stats.csv, but with potentially more accurate data extraction
Battle_Performance_Stats.csv: Sales, Net Profit, OPM, EPS for the last three years

Companies Analyzed
The scripts analyze data for the following companies:
VOLTAS, BLUE STAR, CROMPTON, ORIENT ELECTRIC, HAVELLS, SYMPHONY, WHIRLPOOL
Notes

These scripts scrape public data from Screener.in. Ensure you comply with their terms of service.
The scripts use different methods to extract data, which may result in variations in the output.
Adjust the file paths in the scripts if you want to save the CSV files in a different location.
