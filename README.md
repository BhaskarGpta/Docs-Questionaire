# Docs Questionnaire Project

## Overview
The Docs Questionnaire project is designed to provide an interactive way to query PDF documents. Utilizing the power of Streamlit for the web interface, Langchain for handling language models, and Google Gemini for embeddings, this tool allows users to upload PDF documents and ask questions based on the content of these documents.

## Features
- **PDF Upload**: Users can upload PDF documents to be processed.
- **Text Extraction**: Extracts text from the uploaded PDF documents.
- **Text Splitting**: Splits the extracted text into manageable chunks for processing.
- **Embeddings Generation**: Utilizes Google Generative AI Embeddings to generate embeddings from the text.
- **Vector Store**: Creates a FAISS vector store from the texts for efficient similarity search.
- **Question Answering**: Allows users to ask questions and retrieves answers based on the document's content.

## Installation

To set up the Docs Questionnaire project, follow these steps:

1. Clone the repository to your local machine.
2. Ensure you have Python installed.
3. Install the required dependencies by running:

4. Start the Streamlit app by running:

   
## Usage

After starting the Streamlit app, navigate to the provided URL in your web browser. You will be greeted with an interface where you can upload a PDF document. Once uploaded, the document will be processed, and you can start asking questions based on its content.

## Dependencies

- Streamlit
- Langchain
- Google Gemini
- PyMuPDF (for PDF reading)
- FAISS (for vector storage and retrieval)

## Acknowledgments

- Made by Bhaskar Gupta
- Special thanks to the open-source projects that made this possible: Streamlit, Langchain, and Google Gemini.
