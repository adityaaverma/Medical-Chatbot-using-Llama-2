# Medical-Chatbot-using-Llama-2
## How to Run 
## steps to run the project 

'''bash
$ conda create -n mchatbot python=3.8 -y
'''

'''bash
$ $ conda activate mchatbot
'''
install -r requirements.txt





set pineconeapikey and pineconeenv in a .env file and place it int the folder

This is Basically Llama-2-7b-chat model which is fetches data from pinecone which is a vector database. Pinecone DB is created by using Medical_book.pdf into vectors and the LLM fetches the details from the vector database and ouputs the correctr result.
