# Sales Summary Web App

## Summary
This static web app fetches sales data from a CSV file, calculates the total sales amount, and displays it on a single-page site. Bootstrap 5 is used for styling, loaded from jsDelivr.

## Setup
To deploy this app on GitHub Pages:
1. Fork this repository.
2. Upload your `data.csv` file to the `attachments` directory in your forked repository.
3. Enable GitHub Pages in the repository settings, choosing the main branch as the source.
4. Visit the GitHub Pages URL to access the Sales Summary web app.

## Usage
To access and use the page, use the following URL:
```
https://your-username.github.io/sales-summary?file=data.csv
```
Replace `your-username` with your GitHub username. You can optionally pass a `file` query parameter to specify the CSV file to load.

## Code Explanation
The HTML and JavaScript code in this app:
- Fetches the specified CSV file and handles trailing newlines and empty rows.
- Parses the data, calculates the total sales amount from the sales column, and updates the DOM to show the total in the `#total-sales` element.

## License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).