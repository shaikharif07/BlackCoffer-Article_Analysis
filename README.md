# Text Analysis Project

Overview
This project is a Python-based text analysis tool designed to perform various text analysis tasks on a collection of articles. It includes web scraping, sentiment analysis, text statistics, and data merging, providing valuable insights into the content of the articles.

Project Structure
The project is structured as follows:

Data Extraction: It starts by reading a list of URLs from an Excel file, which are assumed to point to articles or web pages.

Web Scraping: For each URL, the script fetches the web page content, extracts the title and paragraphs, and saves them to text files.

Data Compilation: It compiles the saved data into a DataFrame using the Pandas library, creating columns for "Title" and "Article."

Text Preprocessing: The script performs basic text preprocessing, such as removing commas from the articles.

Stopword Handling: It combines multiple stopwords lists into a single file and reads them for text analysis.

Sentiment Analysis: Sentiment analysis is performed using the TextBlob library to calculate polarity and subjectivity scores for each article.

Text Statistics: Various text statistics are computed, including average sentence length, percentage of complex words, Fog index, and more.

Data Merging: The script reads additional data from an Excel file and merges it with the text analysis results to create a final DataFrame.

Data Export: The final DataFrame is exported to a CSV file named "TextAnalysisOutput1.csv."
