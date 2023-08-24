# Apartment-Searching
Using selenium to search apartments

## How it Works

1. **Setup**: The project uses Python with Selenium and Beautiful Soup libraries to interact with apartment listing websites.

2. **City Selection**: You can choose the city you're interested in exploring apartments in. The tool will focus on this city during the process.

3. **Data Collection**: The tool simulates browsing through multiple pages of apartment listings and captures details like apartment complex names, addresses, prices, and amenities.

4. **Amenities Mapping**: The tool sorts out different amenities mentioned in the listings and gives each a unique ID. This helps in understanding and comparing apartments based on their offerings.

5. **Data Organization**: The collected information is organized into a structured format, making it easier to analyze.

6. **Price Ranges**: The tool calculates the price range for each apartment, providing the lowest and highest rent they're asking for.

7. **Data Output**: The organized data is saved in files that can be further analyzed using tools like Excel or specialized software.

## Files Included

- `apartment_search_tool.ipynb`: The Python script that performs web scraping, data collection, and data organization.
- `apartment_search_tool.ipynb` will however, produce 3 csv files one can use for further analysis

## Usage

1. Install the required Python packages listed in the `apartment_search_tool.ipynb` file.
3. Run the `apartment_search_tool.py` script.
4. Choose a city and let the tool gather apartment data.
5. Find the collected data in the CSV files for further analysis.
