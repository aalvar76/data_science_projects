## Movies Data Extraction and Storage

This Python script is designed to extract data from a web page containing information about the top 50 highly-ranked films. It utilizes various libraries such as `requests`, `sqlite3`, `pandas`, and `BeautifulSoup`.

### Purpose
The script serves the following purposes:
- Extracts data from a specified URL.
- Parses the HTML content of the webpage using BeautifulSoup to extract relevant information.
- Stores the extracted data into a pandas DataFrame.
- Saves the DataFrame as a CSV file named `top_50_films.csv`.
- Creates a SQLite database named `Movies.db`.
- Stores the extracted data in a table named `Top_50` within the SQLite database.

