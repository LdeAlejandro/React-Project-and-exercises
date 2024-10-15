
Summary of the Request:

Objective: Create components for a stock market website that allows users to view real-time stock charts and buy and sell stocks.

Technical Specifications:

Tech Stack: Frontend: ReactJS
Frontend Port: 5000
Implementation Details:

Dashboard: Displays stock information for various companies.
Components: Each component should include:
Company name
Current stock price
Real-time stock chart (using chart.js or similar)
Button to buy stocks
Navbar:

Includes links to "Home," "My_Stocks," and "My_Fund," as well as a search box for searching specific companies.
Homepage Functionalities:

Loads information via a GET request from the provided link.
Each stock card will have appropriate data-testid attributes.
Stock Card Functionalities:

Increment and decrement the quantity of stocks.
Display the total stock price.
My_Stocks Page:

Shows information about all stocks purchased.
Each component should include:
Company name
Number of stocks purchased
Sell button
Displays the total net value of all stocks.
Sell Form:

Includes the company name and quantity of stocks to be sold.
Button to confirm the sale.
My_Fund Page:

Displays the total fund available (Rs 10,000).
Shows the total price of stocks purchased and the remaining balance.
Additional Notes:

Components must have data-testid attributes for testing and should not be changed.
Instructions for starting the development server and running tests.
Testing and Submission Instructions:

The project can be tested at the provided link, with specific instructions on how to run tests and submit code.

chart: 'https://s3-ap-southeast-1.amazonaws.com/he-public-data/db12a41f8.json
