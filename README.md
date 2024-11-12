# Q&A RAG Application

![image](https://github.com/user-attachments/assets/b2a35f30-9601-4499-aab0-acd75750d4e7)                  
     
## Overview
This project is a Q&A Retrieval-Augmented Generation (RAG) application that utilizes Nvidia Nim API-Key for enhanced performance. The application is designed to handle PDF documents, allowing users to upload a PDF and retrieve answers based on their questions. The application uses advanced machine learning and natural language processing techniques to provide accurate and quick responses.
     
## Features    
- **PDF Upload**: Users can upload PDF documents to the application.     
- **Question Answering**: The application answers questions based on the content of the uploaded PDF.
- **High Performance**: Leveraging Nvidia Nim API for fast and efficient processing.                  
       
## Libraries and Technologies Used
- **fitz**: For handling PDF documents.
- **faiss**: For efficient similarity search.
- **sentence_transformers**: For embedding sentences.
- **openai**: For using OpenAI's language models.
- **Nvidia Nim API**: For enhanced performance with Nvidia's technology.

## Pretrained Models
- **paraphrase-MiniLM-L6-v2**: For generating sentence embeddings.
- **meta/llama3-8b-instruct**: For question answering tasks.

## Setup and Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/QA-RAG-Application.git
    cd QA-RAG-Application
    ```

2. Install the required libraries:
    ```
    pip install fitz faiss-cpu sentence-transformers openai
    ```

3. Set up Nvidia Nim API:
    - Obtain your API key from Nvidia Nim https://www.nvidia.com/en-in/ai/ .
    - Set the API key in your environment variables or configuration file.

## Usage
1. Run the application:
    ```bash
    python app.py
    ```

2. Upload a PDF document.

3. Ask a question based on the content of the uploaded PDF.

4. Receive the answer generated by the application.

## Results
The application performs exceptionally well at basic to intermediate level questions, providing fast and accurate responses thanks to the integration with Nvidia's technology.

## Future Work
- Improve handling of complex queries.
- Incorporate more advanced models and fine-tuning techniques.


