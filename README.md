# Web-Crawler-with-Python-Flask-interface

**Web-Crawler** -- Developed using python's library Beautiful Soup, which parsed the HTLM content of the website and extracts the title, authors, data published, keywords and abstract of articles published by members of the Research Centre for Computational Science and Mathematical Modelling (CSM) at Coventry University. The data is stored in a pandas data frame and stored locally in csv format.

**Reverse-index** -- The reverse index maps each unique term
found in the documents and stores the corresponding document IDs for each term in the index.
The index plays a crucial role in the search engine's retrieval process. When a user enters a search
query, the search engine looks up the query terms in the index to quickly identify the documents that
contain those terms. This approach is much faster than searching through all the documents in the
search engine's database individually.

**Web Interface** -- The web interface was developed using Flask and enables users to interact with the search engine and
easily perform searches on the indexed documents. Users can enter search queries and view search
results
