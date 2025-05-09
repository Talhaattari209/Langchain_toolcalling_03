# Langchain Tool Calling for Market Analysis

This project demonstrates the use of LangChain for analyzing Future Contracts market data with Chain of Thought (COT) reporting capabilities.

## Project Structure
- `COT_REPORT.ipynb` - Jupyter notebook containing market data visualization using matplotlib
- `Lang_func_toolcalling_01.ipynb` - Main implementation notebook with LangChain tool calling setup
- `README.md` - Project documentation

## Dependencies
The project requires the following Python packages:
- langchain
- langchain-text-splitters 
- langchain-community
- langchain-google-genai
- langchain-pinecone
- matplotlib
- pypdf
- tqdm
- uuid
- pinecone-client

## Features
- Integration with Google Generative AI using `ChatGoogleGenerativeAI`
- Vector storage using Pinecone
- Conversation memory management
- Custom tool implementations for data analysis
- Visualization capabilities using matplotlib

## Setup
1. Install the required dependencies:
```bash
pip install --upgrade langchain-text-splitters langchain-community langchain-google-genai langchain-pinecone
pip install -qU pypdf tqdm uuid matplotlib
pip install langchain --upgrade
