#WEBSCRAPPER FOR JOB INFORMATION

##WebScrapper built using python to retrieve data from the website FakeJobs and print out the jobs.


## Requirements

- Python 3.x
- BeautifulSoup (for HTML parsing)
- Requests (for making HTTP requests)


## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/ThokozaniTshabalala/WEB_SCRAPPING
    ```

2. Navigate to the project directory:

    ```bash
    cd WEB_SCRAPPING
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```
## Usage

1. Open the `scraper.py` file.

2. Locate the `url` variable and replace it with the URL of the website you want to scrape job information from.

    ```python
    url = 'https://example.com/jobs'
    ```

3. Run the scraper:

    ```bash
    python scraper.py
    ```

4. The scraper will print out job information from the specified website.

## Disclaimer

Ensure that you review and comply with the terms of service of the website you are scraping. Respect the website's robots.txt file, and do not overload the server with too many requests.