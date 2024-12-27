# Web Scraping with Python

## Overview

This repository contains a Jupyter Notebook that demonstrates web scraping techniques using Python. It focuses on extracting and processing structured data from web pages, such as tables and lists, and organizing the results into an analyzable format.

## Features

- Extract data from web pages using `requests` and `BeautifulSoup`.
- Process and clean scraped data using utility functions.
- Organize data into structured formats with `pandas` for further analysis.
- Includes helper functions for tasks like:
  - Parsing dates and times
  - Extracting specific column data
  - Evaluating conditions (e.g., booster landing statuses)

## Libraries Used

- **`requests`**: For making HTTP requests and fetching web page content.
- **`BeautifulSoup` (from `bs4`)**: For parsing HTML and navigating the DOM.
- **`pandas`**: For data manipulation and organization.
- **`re`**: For handling regular expressions in data cleaning.
- **`unicodedata`**: For Unicode normalization.
- **`sys`**: For system-level operations.

## Getting Started

### Prerequisites

Ensure you have the following installed:

- Python 3.7 or later
- Jupyter Notebook
- The required Python libraries (install them with `pip install -r requirements.txt`)

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/web-scraping.git
   ```
2. Navigate to the project directory:
   ```bash
   cd web-scraping
   ```
3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Usage

1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook webscraping.ipynb
   ```
2. Follow the step-by-step instructions in the notebook to understand and execute web scraping tasks.

## Functions Overview

- **`date_time(table_cells)`**: Parses date and time from table cells.
- **`booster_version(table_cells)`**: Extracts booster version information.
- **`landing_status(table_cells)`**: Evaluates and returns the landing status.
- **`get_mass(table_cells)`**: Extracts mass data.
- **`extract_column_from_header(row)`**: Retrieves column names from a table header row.

## Output

The notebook generates structured outputs suitable for analysis, such as data frames containing cleaned and processed web data.
