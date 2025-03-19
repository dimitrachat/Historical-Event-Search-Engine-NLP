# Historical-Event-Search-Engine-NLP
A search engine for historical events, leveraging web scraping, Natural Language Processing (NLP), and advanced techniques like Word2Vec, BERT, LLMs, and RAG systems. The project focuses on extracting, analyzing, and retrieving relevant information from Wikipedia to provide insights into historical events.
## Overview
This project creates a search engine for historical events by scraping data from Wikipedia and applying advanced NLP techniques like Word2Vec, BERT, Large Language Models (LLMs), and Retrieval-Augmented Generation (RAG) systems. The goal is to provide accurate and context-aware insights into historical events.
## Introduction
The internet is a vast source of information on historical events. This project scrapes data from Wikipedia, preprocesses it, and applies NLP techniques to create a search engine that provides accurate and context-aware insights into historical events like World War II, the Israel-Palestine conflict, and more.

## Scraping Data
Data is scraped from Wikipedia using the BeautifulSoup library. The scraped data is saved in JSON files for further processing. The scraping process involves:
- Crawling web pages.
- Parsing HTML to extract relevant data.
- Storing data in a structured format.

## Text Preprocessing & Cleaning
Text data is preprocessed to ensure efficient indexing and accurate retrieval. The preprocessing steps include:
- Sentence tokenization.
- Lemmatization.
- Stopwords removal.
- Lowercasing.
- Word tokenization.

## Word2Vec
Word2Vec is used to represent words as vectors, enabling semantic understanding of queries and documents. The model helps in:
- Improving search results by understanding synonyms and related terms.
- Ranking content based on semantic similarity to queries.

## BERT
BERT (Bidirectional Encoder Representations from Transformers) is used for contextual understanding of queries and documents. It enhances search engine performance by:
- Understanding the context of words in queries.
- Providing more accurate and relevant search results.

## LLMs
Large Language Models (LLMs) like GPT-3.5-turbo are used to generate conversational and context-aware responses to historical queries. LLMs improve the interactivity and relevance of search results.

## RAG System
The Retrieval-Augmented Generation (RAG) system combines retrieval-based methods with generative models to provide accurate and comprehensive responses to complex queries. It:
- Retrieves relevant documents from a predefined corpus.
- Generates well-structured responses based on the retrieved documents.

## Conclusion
This project demonstrates the potential of combining web scraping with advanced NLP techniques to create intelligent search engines for historical research. The integration of Word2Vec, BERT, LLMs, and RAG systems enhances the accuracy and relevance of search results, providing deeper insights into historical events.

## Bibliography
- Advanced Word Embeddings: Word2Vec, GloVE, and FastText. Medium.
- BERT. Hugging Face.
- Contextual Search Engine with LLM. Medium.
- Evaluating LLM Systems: Best Practices. Medium.
- Retrieval Augmented Generation (RAG) – Nextra.

## Requirements
- Python 3.x
- [BeautifulSoup4](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- NLTK
- Gensim (for Word2Vec)
- Transformers (for BERT)
- OpenAI API (for LLM functionality, if needed)
- Other dependencies as listed in `requirements.txt`
