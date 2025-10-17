# Project README

## Overview
This project is a single-page web application designed to display the total sum of sales data retrieved from an attached `data.csv` file. It utilizes modern JavaScript (Fetch API) for data retrieval and parsing, and leverages Bootstrap 5 for professional styling.

## Setup
Since this is a single-page application (`index.html`), setup is minimal:
1. Ensure the `data.csv` file is available in the same directory as `index.html`.
2. Open `index.html` in any modern web browser.

## Usage
Upon loading the page:
1. The JavaScript script immediately fetches `data.csv`.
2. The script parses the CSV content, specifically locating and summing values from the `sales` column.
3. The document title is set to 'Sales Summary student-test-seed'.
4. The calculated total sales figure (expected to be 1650.75) is displayed within the `id="total-sales"` element on the page, styled using Bootstrap 5 components.
5. If data fetching or parsing fails, an error message ('N/A' or 'ERROR') will be displayed instead of the sales total.