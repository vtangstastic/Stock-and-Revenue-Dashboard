# Stock-and-Revenue-Dashboard
## Stock-and-Revenue-Dashboard

This project is part of the IBM Data Science Certification program, where stock and revenue data for Tesla and GameStop are extracted and analyzed.

### Question 1: Use yfinance to Extract Stock Data

1. Use the `yfinance` library to extract stock data for Tesla with the ticker symbol TSLA.
2. Create a ticker object for Tesla.
3. Extract stock information using the `history` function and save it in a DataFrame named `tesla_data`.
4. Set the period parameter to max to get information for the maximum amount of time.
5. Reset the index of the DataFrame and display the first five rows of the data.

### Question 2: Use Webscraping to Extract Tesla Revenue Data

1. Use the `requests` library to download the webpage containing Tesla revenue data.
2. Save the text of the response as a variable named `html_data`.
3. Parse the HTML data using BeautifulSoup.
4. Extract the table with Tesla revenue data and store it in a DataFrame named `tesla_revenue`.
5. Remove commas and dollar signs from the Revenue column.
6. Drop any null or empty strings in the Revenue column.
7. Display the last five rows of the `tesla_revenue` DataFrame.

### Question 3: Use yfinance to Extract Stock Data for GameStop

1. Use the `yfinance` library to extract stock data for GameStop with the ticker symbol GME.
2. Create a ticker object for GameStop.
3. Extract stock information using the `history` function and save it in a DataFrame named `gme_data`.
4. Set the period parameter to max to get information for the maximum amount of time.
5. Reset the index of the DataFrame and display the first five rows of the data.

### Question 4: Use Webscraping to Extract GameStop Revenue Data

1. Use the `requests` library to download the webpage containing GameStop revenue data.
2. Save the text of the response as a variable named `html_data`.
3. Parse the HTML data using BeautifulSoup.
4. Extract the table with GameStop revenue data and store it in a DataFrame named `gme_revenue`.
5. Remove commas and dollar signs from the Revenue column.
6. Drop any null or empty strings in the Revenue column.
7. Display the last five rows of the `gme_revenue` DataFrame.

### Question 5: Plot Tesla Stock Graph

1. Use the `make_graph` function to graph the Tesla stock data.
2. Provide a title for the graph.
3. Note that the graph will only show data up to June 2021.

### Question 6: Plot GameStop Stock Graph

1. Use the `make_graph` function to graph the GameStop stock data.
2. Provide a title for the graph.
3. Note that the graph will only show data up to June 2021.
