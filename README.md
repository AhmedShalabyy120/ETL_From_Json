# USA.gov Click Data Analysis

This repository contains Python code for processing and analyzing USA.gov click data. The code reads a JSON file, converts it to a Pandas DataFrame, and extracts relevant information from the dataset. This code provides insights into web browsers, operating systems, URLs, locations, and timestamps of the click data.

## Prerequisites

Before using this code, ensure that you have the following prerequisites installed on your system:

- Python 3.x
- NumPy
- pandas
- datetime



# Code Explanation

This code performs the following tasks:

1. **Reads the JSON Data**: It reads the data from the `usa.gov_click_data.json` file and converts it into a Pandas DataFrame.

2. **Data Extraction**: The code extracts key information from the DataFrame, including web browsers, operating systems, URLs, locations, and timestamps.

3. **Creating df_final**: A new DataFrame named `df_final` is created with selected columns.

4. **Handling Missing Data**: Rows with missing values are dropped from the `df_final` DataFrame.

5. **Exporting Results**: The final DataFrame is exported to a CSV file named `task2.csv`.

# Data Columns in `task2.csv`

The output CSV file, `task2.csv`, contains the following columns:

- **web_browser**: The web browser used by the visitor.
- **os**: General operating system information.
- **operating_system**: More detailed information about the operating system.
- **url**: The original URL from which the user came.
- **to_url**: The URL the user navigated to.
- **city**: Location information.
- **Latitude**: Latitude coordinate.
- **longitude**: Longitude coordinate.
- **TimeZone**: Time zone information.
- **time_in**: Timestamp in the "YYYY-MM-DD HH:MM:SS" format.
- **time**: Timestamp when the click occurred.

Feel free to explore and analyze the USA.gov click data using this code.


