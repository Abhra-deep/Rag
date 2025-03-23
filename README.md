# RAG Chatbot Project

## Overview
This project implements a custom chatbot using a **Retrieval-Augmented Generation (RAG)** pipeline. The chatbot utilizes LangChain and LlamaIndex to extract relevant information from Brainlox course documents and provide accurate, context-aware responses to user queries.

## Features
- Efficient document processing using `pdfplumber`.
- Semantic search and ranking using ChromaDB.
- Contextual answer generation using OpenAI's GPT model.
- Scalable and customizable RAG pipeline.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/user/rag-chatbot-project.git
    cd rag-chatbot-project
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Place your PDF documents inside the `data/` directory.
2. Run the application:
    ```bash
    python app.py
    ```
3. Access the chatbot via the API endpoint:
    ```
    http://localhost:5000/chat
    ```
4. Provide a query, and the chatbot will generate a contextually accurate response.

## Configuration
- Update the API keys and model configurations in `config.py`.
- Adjust the chunk size, embedding model, and search parameters as needed.

## Contributing
Contributions are welcome! Feel free to submit a pull request or open an issue.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For questions or suggestions, reach out to [your-email@example.com](mailto:abhradeepchandrapaul@gmail.com).

