# Pharmacy Scraper

This project scrapes pharmacy data from a website and stores it in a list.

## Installation

Clone the repository and install the required packages:
    ```bash
    git clone <repository_url>
    cd pharmacy-scraper
    pip install -r requirements.txt
    ```

## Usage

1. Clone the repository:
    ```bash
    git clone <repository_url>
    ```
   
2. Navigate to the project directory:
    ```bash
    cd pharmacy-scraper
    ```
   
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the scraper script:
    ```bash
    python scraper.py
    ```

5. The script will fetch the data and print the number of pharmacies found.

Note: Make sure you have Python and `pip` installed on your system.

## Dependencies

The following Python libraries are required to run the project:

- `requests`: For making HTTP requests to fetch web pages.
- `BeautifulSoup4`: For parsing HTML and extracting data from web pages.

You can install these dependencies using the following command:
    ```bash
    pip install -r requirements.txt
    ```

The `requirements.txt` file should contain:
    ```
    requests
    beautifulsoup4
    ```

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
