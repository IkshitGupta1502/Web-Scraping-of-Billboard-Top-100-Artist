# Web-Scraping-of-Billboard-Top-100-Artist
This Python script utilizes web scraping techniques to extract the current top 100 artists from the Billboard website. The extracted data is then organized into a structured Pandas DataFrame and exported to a CSV file for further analysis.

**Functionality**
-  Web Scraping: The script sends an HTTP GET request to the Billboard Top 100 Artist webpage and parses the HTML content using BeautifulSoup.
-  Data Extraction: The script extracts the ranking, artist name, and weeks on chart for each of the top 100 artists.
-  Data Organization: The extracted data is organized into a Pandas DataFrame for easy manipulation and analysis.
-  CSV Export: The DataFrame is exported to a CSV file, providing a convenient format for further analysis or data visualization.
  
**Code Structure**
The script is divided into the following sections:
-  Importing Libraries: The necessary Python libraries, including requests, BeautifulSoup, and pandas, are imported.
-  Web Scraping and HTML Parsing: The Billboard webpage is scraped and the HTML content is parsed using BeautifulSoup.
-  Data Extraction and Organization: The extracted data is organized into a Pandas DataFrame.
-  CSV Export: The DataFrame is exported to a CSV file.
  
**Requirements**
-  Python 3.x
-  requests library
-  BeautifulSoup library
-  pandas library
