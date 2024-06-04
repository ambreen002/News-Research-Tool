# News Research Tool 📈

## Overview
This tool is a Retrieval-Augmented Generation (RAG) based application that leverages the power of Streamlit, Langchain, and OpenAI to create a dynamic web application for researching and analyzing news articles. It extracts data from specified URLs, processes it, and uses a retrieval-augmented approach to answer questions by retrieving relevant information and generating contextually relevant responses.

## Features
- **URL Input**: Users can input up to three news article URLs via the Streamlit sidebar.
- **Data Processing**: Automatically loads and processes text from provided URLs.
- **Text Splitting**: Splits the article text into segments for better processing.
- **Embedding and Indexing**: Generates embeddings for the text and indexes them using a FAISS index for fast retrieval.
- **Query System**: Users can query the indexed data to retrieve relevant information.
- **Source Display**: Displays the sources of the information retrieved from the query.

## Installation

### Prerequisites
- Python 3.8 or higher
- streamlit
- openai
- python-dotenv
- unstructured
- tiktoken
- faiss-cpu
- langchain-openai
- langchain-community
- libmagic
- python-magic-bin
- python-magic
  
### Environment Setup
1. Clone this repository.

2. Navigate to the project directory:
cd RAG-Tools/News-Research-Tool

3. Install the required packages mentioned in the Prerequisites section.

### Configuration
Create a `.env` file in the root directory and add your OpenAI API key:
OPENAI_API_KEY='your_api_key_here'

## Usage
To run the application:
streamlit run app.py

Open your web browser and go to `http://localhost:8501` to view the app.

## How It Works
1. **Input URLs**: Enter the URLs of the news articles you want to analyze in the sidebar.
2. **Process URLs**: Click the "Process URLs" button to start loading and processing the data.
3. **Query**: Once the data is processed and indexed, you can enter a query in the main interface to search through the indexed data using the RAG-based system.

<img width="1155" alt="image" src="https://github.com/ambreen002/AI-Projects/assets/36915142/62770dd6-1555-4036-8c21-ad79fff86dde">
