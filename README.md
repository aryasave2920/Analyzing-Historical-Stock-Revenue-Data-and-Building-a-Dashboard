# Analyzing-Historical-Stock-Revenue-Data-and-Building-a-Dashboard
This jupyter notebook provides an enlightment to the process of web scraping through extracting the stock details of some of the industry leaders stocks
# Stock Data Analysis and Visualization

This project retrieves historical stock data from Yahoo Finance and web-scraped revenue data, then generates interactive graphs for visualization. It analyzes Tesla (TSLA) and GameStop (GME) stock data.

## Project Overview

This Jupyter Notebook (`stock_data_analysis.ipynb`) demonstrates how to:

* Download stock data using `yfinance`.
* Web scrape revenue data using `requests` and `BeautifulSoup`.
* Clean and process the data using `pandas`.
* Visualize the data using `altair`.

## Installation

1.  Clone the repository:

    ```bash
    git clone [repository URL]
    ```

2.  Navigate to the project directory:

    ```bash
    cd [project directory]
    ```

3.  Install the required libraries:

    ```bash
    pip install -r requirements.txt
    ```

    Or, if you don't have a `requirements.txt` file, install them individually:

    ```bash
    pip install yfinance pandas beautifulsoup4 requests altair html5lib
    ```

4. Install jupyter notebook.
    ```bash
    pip install notebook
    ```

## Usage

1.  Open the `stock_data_analysis.ipynb` Jupyter Notebook:

    ```bash
    jupyter notebook
    ```

2.  Run the cells in the notebook sequentially to download data and generate graphs.

3.  Observe the interactive graphs displayed within the notebook.

## Files and Structure

* `stock_data_analysis.ipynb`: Jupyter Notebook containing the data analysis and visualization code.


## Data Sources

* Yahoo Finance: [https://finance.yahoo.com/](https://finance.yahoo.com/)
* Web-scraped revenue data: [https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0220EN-SkillsNetwork/labs/project/revenue.htm](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0220EN-SkillsNetwork/labs/project/revenue.htm)
* Web-scraped stock related data: [https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0220EN-SkillsNetwork/labs/project/stock.html](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0220EN-SkillsNetwork/labs/project/stock.html)

## Dependencies

* `yfinance`
* `pandas`
* `BeautifulSoup4` (`bs4`)
* `requests`
* `altair`
* `html5lib` (optional)


## Author

Arya Save / aryasave2920
