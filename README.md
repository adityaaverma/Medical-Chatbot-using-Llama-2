# Medical Chatbot using Llama-2
## Project Overview

This project involves creating a medical chatbot utilizing the Llama-2-7b-chat model in combination with Pinecone, a vector database. The chatbot fetches relevant medical information from a preprocessed medical book stored as vectors in Pinecone and delivers accurate responses based on user queries.

## Steps to Run the Project

1. **Set Up the Python Environment**

    Create a new conda environment with Python 3.8:
    ```bash
    $ conda create -n mchatbot python=3.8 -y
    ```

    Activate the newly created environment:
    ```bash
    $ conda activate mchatbot
    ```

2. **Install Required Dependencies**

    Install the necessary Python packages listed in the `requirements.txt` file:
    ```bash
    $ pip install -r requirements.txt
    ```

3. **Configure Pinecone API**

    Set up your Pinecone API key and environment variables. Create a `.env` file in the project directory with the following content:
    ```bash
    PINECONE_API_KEY=your_pinecone_api_key
    PINECONE_ENV=your_pinecone_environment
    ```

## Project Description

The chatbot is based on the Llama-2-7b-chat model, which interacts with a vector database created using Pinecone. The vector database is populated by converting the content of a medical book (Medical_book.pdf) into vectors. When a user interacts with the chatbot, the LLM queries the vector database to retrieve relevant information and provides accurate medical responses.

This architecture ensures that the chatbot can efficiently fetch and deliver precise medical information based on user queries, leveraging the powerful combination of Llama-2-7b-chat and Pinecone.
