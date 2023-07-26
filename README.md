# ICS_SearchEngine_UCI
Created a search engine from the ground up that is capable of handling two thousand documents or Web pages from the School of Information and Computer Science (ICS) at University of California (UCI).


This project is a web-based search engine powered by Python's Flask framework. It features various Information Retrieval techniques including text processing, indexing, and a ranking algorithm, all implemented from scratch. The search engine includes a simple and intuitive user interface.

Features:
Text Processing: The system uses NLTK to perform tokenization and stemming on documents.
Indexing: We developed an inverted indexer to store the processed documents. It maps terms to the documents they appear in, alongside their TF-IDF scores and importance.
Ranking: Documents are ranked based on their TF-IDF scores, providing a list of top search results.
Web Scraping: The BeautifulSoup library is used to parse HTML and extract useful information.
Summary Generation: We use OpenAI's GPT-3 model to generate a summary of search results.
Flask Web Application: The search engine is hosted on a Flask server, which handles GET and POST requests and renders the user interface.
