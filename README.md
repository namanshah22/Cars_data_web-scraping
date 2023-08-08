# Car Dealer Web Scraping

This project demonstrates web scraping to extract car dealer information from the cars.com website using the BeautifulSoup library in Python.

## Project Description

The goal of this project is to collect car dealer information, including car details such as name, mileage, dealer name, rating, review count, and price, from the cars.com website using web scraping techniques. The information is extracted and stored in a Pandas DataFrame, which is then saved to an Excel file for further analysis.

## Requirements

- Python (>= 3.6)
- BeautifulSoup (`beautifulsoup4`)
- Requests (`requests`)
- Pandas (`pandas`)

## Part 1 - Single Page

1. Import necessary libraries (`BeautifulSoup`, `requests`, `pandas`).
2. Perform an HTTP request to the cars.com website.
3. Use `BeautifulSoup` to parse the HTML content.
4. Find and extract car dealer information from the parsed content.
5. Create a Pandas DataFrame from the extracted information.
6. Clean the extracted data if necessary.
7. Output the DataFrame to an Excel file (`car_dealer_single_page.xlsx`).

## Part 2 - Pagination

1. Implement a loop to iterate through multiple pages (1 to 10) of car dealer listings.
2. Modify the website URL to fetch results from different pages.
3. Extract car dealer information from each page and append it to the existing DataFrame.
4. Clean the data if necessary.
5. Output the updated DataFrame to an Excel file (`car_dealer_multiple_page.xlsx`).

## Results
The extracted car dealer information is stored in the generated Excel files (car_dealer_single_page.xlsx and car_dealer_multiple_page.xlsx), which can be further analyzed using tools like Microsoft Excel or imported into other data analysis platforms.
