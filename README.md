# Trading Insights: CHM and Gann Cycles Analysis for Indian Stocks

## Overview

**CHM-and-Gann-Cycles-Analysis** is a data engineering and data science project aimed at extracting 20 years of historical data for all stocks on the Indian Stock Market. This project applies two key technical analysis methods—CHM (Cycle Harmonic Method) and Gann Cycles—to identify potential trading opportunities.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Data Sources](#data-sources)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Features

- Collect historical stock data for the past 20 years from Yahoo Finance.
- Implement CHM and Gann Cycles methods for identifying trading opportunities.
- Save and manage progress with error handling to ensure data integrity.
- Output processed data in a user-friendly CSV format for further analysis.

## Technologies Used

- Python
- Selenium
- Pandas
- NumPy
- Matplotlib (for visualization, if applicable)
- Yahoo Finance API (for data collection)

## Getting Started

To get a local copy up and running, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/CHM-and-Gann-Cycles-Analysis.git
   cd CHM-and-Gann-Cycles-Analysis
   ```

2. **Install the required packages:**

   You can install the required packages using pip:

   ```bash
   pip install -r requirements.txt
   ```

3. **Set up the WebDriver:**

   Ensure you have the Chrome WebDriver installed and added to your system PATH, or adjust the `init_driver` function to point to the WebDriver location.

## Usage

1. **Edit the `bse_stocks` list in the `main` function:**

   Update the list to include the stock symbols you want to analyze.

2. **Run the script:**

   Execute the main script to start fetching historical stock data:

   ```bash
   python main.py
   ```

3. **Analyze the output:**

   The data will be saved in the specified output CSV file. You can then analyze the data using your preferred tools or methods.

## Data Sources

- Historical stock data is collected from Yahoo Finance.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Inspired by the need for effective trading strategies in the Indian Stock Market.
- Thanks to contributors and libraries that facilitate data scraping and analysis.
