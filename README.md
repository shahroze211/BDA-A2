
Sure, here's a detailed README file based on the provided code:

Search Engine README
This repository contains the implementation of a basic search engine using Python. The search engine is capable of indexing documents, calculating TF-IDF (Term Frequency-Inverse Document Frequency) representations, and processing user queries to retrieve the most relevant documents.

Features
Document Indexing: The search engine reads data from a CSV file, tokenizes the text content of each document, and creates a vocabulary with unique term IDs. It calculates the Term Frequency (TF) for each document, which represents the frequency of each term in the document.

TF-IDF Calculation: After indexing the documents, the search engine calculates the Inverse Document Frequency (IDF) for each term in the vocabulary. It then computes the TF-IDF weights for each term in each document. TF-IDF is a statistical measure used to evaluate the importance of a term in a document relative to a collection of documents.

Query Processing: Users can input queries, and the search engine preprocesses the query text by tokenizing, lowercasing, stemming, and removing stopwords. It then calculates the TF-IDF representation for the query. Using cosine similarity, the search engine ranks the documents based on their similarity to the query and returns the top-ranked documents as search results.

User Interaction: The search engine allows users to input queries interactively through the command line interface.

Requirements
To run the search engine, ensure you have the following dependencies installed:

Python 3.x
NLTK (Natural Language Toolkit) library
scikit-learn library (for cosine similarity calculation)
You can install NLTK and scikit-learn using pip:

Copy code
pip install nltk scikit-learn
Before running the code, you also need to download the NLTK stopwords dataset. You can do this by running the following Python code once:

python
Copy code
import nltk
nltk.download('punkt')
nltk.download('stopwords')
Usage
Clone the Repository: Clone this repository to your local machine.

Prepare Data: Place your CSV file containing text data in the repository directory. Ensure that the CSV file has at least four columns, and the text content of each document is in one of the columns.

Run the Code: Execute the main Python script (search_engine.py or any other relevant filename) to run the search engine. Follow the on-screen instructions to input queries and retrieve search results.

Interact with the Search Engine: Input queries through the command line interface, and the search engine will process the queries and return the most relevant documents based on TF-IDF and cosine similarity.

Code Structure
search_engine.py: Main Python script containing the implementation of the search engine.
data/sample.csv: Sample CSV file used for testing the search engine.
README.md: README file providing an overview of the search engine and instructions for usage.
Acknowledgments
The search engine implementation uses concepts from information retrieval and natural language processing.
NLTK and scikit-learn libraries are used for text preprocessing and cosine similarity calculation, respectively.


*Cluster*
![4 nodes_present](https://github.com/shahroze211/BDA-A2/assets/157700960/e53ec5d6-8629-46e1-b2a7-26a6b888f314)
![4 VMs hadoop error](https://github.com/shahroze211/BDA-A2/assets/157700960/5f23cb10-0ad0-4b3c-80a2-41322dabb3be)
