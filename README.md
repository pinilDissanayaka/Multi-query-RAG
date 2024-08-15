# Multi-query-RAG

This repository contains a Multiple-Query Retrieval-Augmented Generation (RAG) application that integrates advanced language modeling and retrieval techniques to provide highly accurate and contextually relevant information. This project leverages LangChain, the Mistral-8X7B-32768 large language model, Hugging Face embeddings, the Pinecone vector database, and a SemanticChunker to achieve optimal results.

## Features
- LangChain Framework: Utilizes LangChain to manage and streamline the interaction between the language model and the retrieval system.
- Mistral-8X7B-32768 Model: A powerful large language model that ensures accurate text generation and comprehension.
- Hugging Face Embeddings: High-quality embeddings from Hugging Face are used for semantic search and understanding.
- Pinecone Vector Database: Efficiently stores and retrieves vector representations of the text data, enabling fast and accurate query responses.
- SemanticChunker: Breaks down text into semantically coherent chunks to improve the relevance and quality of the generated answers.

## Installation
Clone the repository and install the required dependencies:
```
git clone https://github.com/pinilDissanayaka/Multi-query-RAG.git
cd Multi-query-RAG
pip install -r requirements.txt
```

## Usage
- Configure the Environment: Set up your environment variables for accessing the Pinecone database and any other necessary APIs.
- Preprocess Data: Use the SemanticChunker to process your input data, breaking it down into manageable and semantically meaningful chunks.
- Run the Application: Execute the main script to start the application. The system will handle multiple queries, retrieve relevant information from the Pinecone database, and generate responses using the Mistral-8X7B-32768 model.

## Contributing
Contributions are welcome! Please fork this repository and submit a pull request for any improvements or bug fixes.

## Acknowledgments
- [LangChain](https://www.langchain.com/): For providing the framework to build this application.
- [Hugging Face](https://huggingface.co/models?library=sentence-transformers&author=sentence-transformers): For their high-quality embeddings.
- [Pinecone](https://www.pinecone.io/): For the efficient vector database solution.
- [Mistral-8X7B-32768](https://mistral.ai/): For the powerful language modeling capabilities.
