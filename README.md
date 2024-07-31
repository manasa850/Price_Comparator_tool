# Price Comparator Tool

## Description
This repository contains a tool used to compare products on e-commerce websites. The tool focuses on books available on Amazon and Flipkart. It scrapes data from these websites and, based on reviews and ratings, generates the best price for the books.

## Repository Files
- **_amazon_books.ipynb**: Jupyter notebook for scraping book data from Amazon.
- **_flipkart_books.ipynb**: Jupyter notebook for scraping book data from Flipkart.
- **_comparision_tool.ipynb**: Jupyter notebook for comparing the scraped data and identifying the best prices.
- **amazon_books_dataa (1).csv**: CSV file containing the scraped book data from Amazon.
- **flipkart_bookss.csv**: CSV file containing the scraped book data from Flipkart.

## Steps Involved

### 1. Load Data
- Import the scraped datasets from Amazon and Flipkart.

### 2. Data Scraping
- Use the provided Jupyter notebooks to scrape data from Amazon and Flipkart.
- Extract relevant information such as book titles, authors, prices, reviews, and ratings.

### 3. Data Preparation
- Clean and preprocess the scraped data.
- Merge the datasets from both websites for comparison.

### 4. Data Comparison
- Analyze the reviews and ratings to determine the best prices for the books.
- Generate a report or summary of the best deals.

## Technologies Used
- Python
- Web Scraping (BeautifulSoup, Selenium)
- Data Analysis (pandas, numpy)
- Jupyter Notebooks

## Getting Started

### Prerequisites
- Python 3.x
- Required libraries: pandas, numpy, BeautifulSoup, Selenium, Jupyter Notebook

### Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/manasa850/price_comparator_tool.git
    ```
2. Navigate to the project directory:
    ```bash
    cd price_comparator_tool
    ```
3. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Run the `_amazon_books.ipynb` notebook to scrape data from Amazon.
2. Run the `_flipkart_books.ipynb` notebook to scrape data from Flipkart.
3. Load the scraped data into the `_comparision_tool.ipynb` notebook.
4. Execute the comparison tool to find the best prices based on reviews and ratings.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any changes or improvements.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
