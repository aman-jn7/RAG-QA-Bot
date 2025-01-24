# RAG-QA-Bot
An intelligent Question-Answering bot leveraging a Retrieval-Augmented Generation (RAG) model to analyze and interpret financial data from Profit & Loss (P&L) statements.

# Project Overview
This project enables users to upload P&L statements in PDF format and ask financial queries. The system retrieves relevant information using a vector-based search and generates accurate responses using pre-trained language models.

# Key Features
Parses P&L statements from PDF files into structured data.
Uses SentenceTransformers to generate embeddings and stores them in Pinecone for efficient retrieval.
Provides real-time interaction through a user-friendly Streamlit interface.
Handles large documents and supports queries like:
"What is the gross profit?"
"How do operating expenses compare over the year?"

# Technologies Used
Python: Core programming language.
Streamlit: For building the interactive user interface.
SentenceTransformers: To generate embeddings for financial data.
Pinecone: Vector database for fast and efficient retrieval.
PyPDF2: For parsing PDF documents.
Docker: For containerizing the application.

# Usage
Upload a PDF file containing a P&L statement through the Streamlit interface.
Enter a query, such as:
"What is the total revenue for 2023?"
"What is the net income before tax?"
View relevant financial data and generated responses.
Sample Query Results
Query	Response
"What is the gross profit?"	Gross Profit: $135,000
"What is the total operating expense?"	Total Operating Expenses: $60,000
"What is the net income?"	Net Income: $59,200

# Future Improvements
Support for multiple document uploads.
Advanced analytics and visualization of financial trends.
Integration with other financial document formats (e.g., Excel).
