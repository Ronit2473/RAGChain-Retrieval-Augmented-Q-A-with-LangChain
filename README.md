# RAGChain: Retrieval-Augmented Q&A with LangChain
RAGChain: Retrieval-Augmented Q&A with LangChain

Overview

This project is a Simple Generative AI App that leverages LangChain for AI-powered document retrieval and response generation. The app dynamically selects relevant documents using a retriever and passes them to an AI model for answering user queries.

Features

Dynamic Document Retrieval: Uses a retriever to fetch relevant documents before AI processing.

Web Scraping for Data Ingestion: Extracts information from websites using WebBaseLoader.

OpenAI API Integration: Utilizes OpenAI's API to generate responses.

LangSmith Tracking: Enables tracing and monitoring using LangSmith.

Technologies Used

Python

LangChain

OpenAI API

Web Scraping (LangChain Community Loaders)

Environment Variable Management (dotenv)

Setup Instructions

Prerequisites

Python 3.8+

OpenAI API Key

LangChain API Key (for tracking, optional)

Required Python packages: langchain, openai, dotenv

Installation

Clone this repository:

git clone https://github.com/your-repo/simple-genai-app.git
cd simple-genai-app

Create a virtual environment and activate it:

python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

Install dependencies:

pip install -r requirements.txt

Set up environment variables:

Create a .env file and add your API keys:

OPENAI_API_KEY=your_openai_api_key
LANGCHAIN_API_KEY=your_langchain_api_key
LANGCHAIN_PROJECT=your_project_name

Usage

Run the application:

python app.py

Enter your queries, and the AI will fetch relevant documents and generate a response.

Future Improvements

Expand document retrieval sources.

Improve response accuracy using advanced embeddings.

Implement a UI for better user interaction.

License

This project is licensed under the MIT License. Feel free to modify and contribute!

Contributing

Pull requests are welcome! If you have suggestions, create an issue or fork the repo and submit a PR.

For more details, contact Ronit Singha Roy.




