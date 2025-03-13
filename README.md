# Wikipedia Scraper for Polish Parliamentary Election Polls + Data Analysis

## Overview
This project is a web scraper designed to extract opinion polling data from Wikipedia for the Polish parliamentary elections. The extracted data is cleaned, processed, and analyzed using Python.

## Features
- Scrapes polling data from Wikipedia pages.
- Cleans and structures the data for further analysis.
- Supports multiple election years (2023, 2019, 2015, etc.).
- Provides data visualization and statistical insights.

## Technologies Used
- Python
- `BeautifulSoup` (for web scraping)
- `requests` (for fetching web pages)
- `pandas` (for data processing and structuring)
- `numpy` (for numerical operations)
- `scipy.stats` (for statistical calculations)
- `matplotlib` (for data visualization)

## Installation

1. Clone this repository:
   ```sh
   git clone https://github.com/your-username/wikipedia_scraper.git
   cd wikipedia_scraper
   ```

2. Install the required dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage

1. Run the Jupyter Notebook to scrape and process the data:
   ```sh
   jupyter notebook wikipedia_scraper.ipynb
   ```

2. Execute each cell to:
   - Fetch Wikipedia polling data.
   - Clean and preprocess the data.
   - Store the processed data in structured tables.
   - Generate visualizations for analysis.

## Data Sources
The data is sourced from Wikipedia pages:
- [Opinion polling for the 2023 Polish parliamentary election](https://en.wikipedia.org/wiki/Opinion_polling_for_the_2023_Polish_parliamentary_election)
- [Opinion polling for the 2019 Polish parliamentary election](https://en.wikipedia.org/wiki/Opinion_polling_for_the_2019_Polish_parliamentary_election)
- [Opinion polling for the 2015 Polish parliamentary election](https://en.wikipedia.org/wiki/Opinion_polling_for_the_2015_Polish_parliamentary_election)

## Contributing
Contributions are welcome! If you find any issues or want to add features, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For any questions, feel free to reach out or open an issue on GitHub.

