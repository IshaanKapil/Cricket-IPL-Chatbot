# Cricket-IPL-Chatbot
The Cricket &amp; IPL Chatbot uses web scraping to collect data from blogs, Wikipedia, and PDFs as the sources. It preprocesses the text, removes irrelevant content, and applies TF-IDF and Cosine Similarity for query matching, generating accurate responses through the chatbot based on the structured corpus.
Features
1) Web Scraping: The chatbot scrapes data from blog articles, Wikipedia, and PDF documents related to Cricket and IPL.
2) Text Preprocessing: The corpus undergoes text cleaning to remove irrelevant content (e.g., special characters, stopwords, URLs).
3) TF-IDF & Cosine Similarity: The text data is processed using TF-IDF vectorization and Cosine Similarity to rank and retrieve the most relevant responses to user queries.
4) Mini Chatbot: The chatbot answers Cricket and IPL-related queries based on the pre-built corpus.
   
Installation
1) Clone the Repository:
Clone the repository to your local machine:
git clone https://github.com/your_username/Cricket-IPL-Chatbot.git

2) Navigate to the Project Folder:
cd Cricket-IPL-Chatbot

3) Run the Jupyter Notebook:
Open the Jupyter notebook Cricket_ChatBot.ipynb:
jupyter notebook Cricket_ChatBot.ipynb

Usage
After running the Jupyter notebook, interact with the chatbot by typing any Cricket or IPL related queries.
The chatbot will search the corpus and return relevant responses based on TF-IDF matching and Cosine Similarity.

Technologies Used
1) Python for building the chatbot.
2) BeautifulSoup and Requests for web scraping blog content.
3) PyPDF2 for extracting text from PDFs.
4) NLTK for text preprocessing (e.g., stopwords removal).
5) scikit-learn for TF-IDF vectorization and Cosine Similarity.

Corpus Sources
1) Wikipedia: Retrieved using the wikipedia Python package for the Cricket summary.
2) Blog Article: Scraped from the IPL success story blog using BeautifulSoup and Requests.
URL: IPL Success Story
3) PDF: Extracted from the PDF containing basic Cricket rules using PyPDF2.
   
How It Works
1) Corpus Creation: The chatbot gathers text from various online sources, including Wikipedia, blogs, and PDFs.
2) Text Preprocessing: The text is cleaned by removing irrelevant content, such as special characters and stopwords, to make the data more suitable for TF-IDF vectorization.
3) Query Matching: The chatbot processes the user query using Cosine Similarity to compare it with the stored content in the corpus and returns the most relevant information.

Summary
This Cricket & IPL Chatbot project demonstrates how to use TF-IDF and Cosine Similarity for a domain-specific question-answering system using a static corpus built from web scraping and document extraction. The chatbot can be enhanced with real-time data sources and deployed as an interactive web application in the future.
