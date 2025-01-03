# Retrieval-Augmented Generation (RAG) Chatbot for Financial Analysis

## Overview
This repository contains the implementation of a Retrieval-Augmented Generation (RAG) chatbot designed for analyzing financial metrics and trends in the automotive sector. It focuses on Annual Reports of Tesla, BMW, and Ford, enabling efficient extraction, analysis, and query answering about revenue, profits, growth trends, and comparative analyses.

## Features
* Data Extraction: Automates the extraction of key financial metrics from Annual Reports (PDFs).
* Query Handling: Answers financial and performance-related questions with support for follow-up queries.
* Terminal Interface: A simple console-based interface for interacting with the chatbot.
* Extensibility: Modular design for adapting to other datasets or industries.

## Technologies Used
* Python: Core programming language.
* RAG Model: Combines retrieval-based and generative AI techniques.
* PyPDF2: Processes and extracts text from PDF files.
* OpenAI GPT API: For generating contextually accurate responses.


## Dependencies
The code can be implemented in Python 3.8 or higher. Install the following and import them to be able to run the codes.
```
flask
openai
faiss-cpu
sentence-transformers
pdfplumber
numpy
```
