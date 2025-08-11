Company name : CODETECH IT Solutions
Name : Shreya Akhilesh kumar singh
INTERN ID : CT04Dh2687
Domain : Python
Duration : 4v week 
Mentor : Neela Santosh 

📈 Stock Price Visualization (Apple Inc. Example)
This Python script fetches historical stock price data for a given ticker symbol (in this example, AAPL - Apple Inc.) from Yahoo Finance and visualizes the closing price trend over the last 6 months.

🔹 Features
Fetches historical stock data using yfinance.

Automatically calculates the date range (last 180 days).

Displays the first few rows of the downloaded dataset for quick inspection.

Plots an interactive and visually appealing closing price trend chart using Matplotlib and Seaborn.

📊 Output
The script generates a line chart showing the stock's closing prices over the selected time range, with:

X-axis → Date

Y-axis → Closing Price (USD)

Grid lines for better readability

Legend for clarity

🛠 Requirements
bash
Copy
Edit
pip install pandas numpy yfinance matplotlib seaborn
🚀 Usage
Change the symbol variable to the desired stock ticker (e.g., "TSLA", "MSFT").

Run the script to automatically fetch and visualize the stock's recent performance.

