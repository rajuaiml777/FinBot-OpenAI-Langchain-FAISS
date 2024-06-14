# FinanceBOT: News Research Tool 📊

FinanceBOT is a sophisticated news research tool that leverages natural language processing (NLP) and machine learning (ML) to analyze multiple URLs of news articles. It allows users to input URLs and then query the tool with a question, retrieving relevant information from the input URLs to provide precise answers.

## Overview

FinanceBOT is designed to help you quickly find information in news articles by processing multiple URLs and answering your questions based on the content of these articles.

## Features

- **Input Multiple URLs:** Analyze multiple news articles simultaneously.
- **Natural Language Processing:** Uses OpenAI's powerful NLP capabilities.
- **Machine Learning:** Employs FAISS for efficient text embeddings and retrieval.
- **User-Friendly Interface:** Built with Streamlit for ease of use.

## Usage

### Step 1: Input URLs
1. Open the application in your web browser.
2. In the sidebar, enter the URLs of the news articles you want to analyze.
3. Click the "Process URLs" button to start the analysis process.

### Step 2: Ask a Question
1. Once the analysis is complete, enter your question in the text input field at the top of the page.
2. Click the "Ask" button to retrieve the answer.

### Step 3: View Results
1. The tool will display the answer to your question.
2. If sources are available, they will be displayed below the answer.

### Technical Details
1. Natural Language Processing: Utilizes the OpenAI API for NLP and ML.
2. Text Embeddings: Uses the FAISS vector store for efficient storage and retrieval.
3. Web Application: Built with Streamlit for a seamless user experience.

## Installation

1. **Clone this repository:**
   ```bash
   git clone https://github.com/rajuaiml777/FinBot-OpenAI-Langchain-FAISS.git

2. **Navigate to the project directory:**
   ```bash
     cd FinBot-OpenAI-Langchain-FAISS

3. **Install the required dependencies:**
   ```bash
    pip install -r requirements.txt

4. **Create a .env file and add your OpenAI API key:**
   ```bash
    OPENAI_API_KEY=your_openai_api_key

4. **Create a .env file and add your OpenAI API key:**
   ```bash
    streamlit run app.py



