Text Mining and Co-Occurrence Analysis of Literature

This project analyzes digitized books from Project Gutenberg
 to study word co-occurrence patterns. Using Python, the program scans text files, cleans and tokenizes the data, and identifies words that frequently appear within a given radius of a target word.

Features

Reads and processes large text files from Project Gutenberg.

Cleans text data by removing punctuation, numbers, and non-alphabetic characters.

Tokenizes words and normalizes text for analysis.

Detects co-occurrences of a target word within a defined radius.

Generates frequency counts of words that commonly appear near the target.

Integrates with Google Colab and Google Drive for dataset storage and execution.

Tools & Technologies

Python 3

Google Colab (for execution environment)

Google Drive (for file storage and access)

Standard Python libraries: os, requests, datetime

How It Works

Metadata Setup:

A metadata.txt file provides the range of book IDs and user information.

Example format:

1342
1350
FirstName
LastName


Text Preprocessing:

The program strips punctuation and non-alphabetic characters.

All words are converted to lowercase for consistency.

Co-Occurrence Analysis:

User specifies a target word (e.g., "river") and a radius (e.g., 5).

The script identifies words within the radius of the target and stores them.

A frequency dictionary is generated to show common word associations.

Output Example:

There are 247 lists in co_occurrence for "river"
{'the': 189, 'bank': 42, 'water': 37, 'flow': 12, ...}

Example Use Case

This project demonstrates natural language processing (NLP) fundamentals by identifying semantic associations between words in literary texts. It can be extended for:

Sentiment analysis

Topic modeling

Keyword network visualization

Getting Started

Clone the repository.

Open the notebook in Google Colab.

Mount Google Drive to access text files.

Adjust parameters in the code (target, radius, book range).

Run the script to analyze co-occurrences.

Future Improvements

Add visualization (word clouds, co-occurrence graphs).

Automate downloading books directly from Project Gutenberg.

Expand preprocessing (stopword removal, stemming/lemmatization).

License

This project is for educational purposes.
