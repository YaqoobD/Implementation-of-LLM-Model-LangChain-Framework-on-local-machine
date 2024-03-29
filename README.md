# GPT4All-on-CPU-Only Using LangChain

This project focuses on deploying and utilizing the GPT4All model on a CPU-only computer, such as a MacBook Pro, without the need for a GPU. GPT4All is a locally running, privacy-aware chatbot that does not require internet connectivity or a GPU. It is part of the Nomic AI ecosystem, which enables individuals and organizations to train and deploy customized large language models on consumer-grade CPUs.

## LanChain Framework
LangChain is a powerful framework for building applications powered by language models. It offers data-awareness and agentic capabilities, allowing language models to interact with external data sources and their environment. With LangChain, developers can easily connect language models to their applications and create intelligent, data-driven solutions.

The framework provides modular components that abstract the complexities of working with language models. These components are easy to use and can be customized to fit specific needs. Additionally, LangChain offers pre-built chains, which are ready-made sequences of components designed for specific tasks. These off-the-shelf chains make it easy to get started and accelerate development.

## Installation and Setup
To get started with GPT4All on your CPU-only computer, follow these steps:

* Download the GPT4All model: Obtain the GPT4All model, which is a 4GB file, from the official website. This model will be used with the GPT4All open-source ecosystem software.

* Install Langchain: Langchain is a library used for interacting with language models. Install it on your local machine to retrieve and load documents, split them into smaller chunks, and perform various operations. Langchain will be used alongside GPT4All.

* Embeddings: In this project, embeddings play a crucial role. Embeddings are numerical representations of information, capturing the semantic meaning of the embedded data. As we are working with CPU-only models, we will use the Alpaca native model and the LlamaCppEmbeddings module from Langchain.

* Vector Database: Utilize FAISS, a library for efficient similarity search and clustering of embeddings, to create a vector database. The embeddings of the documents will be stored in this database, enabling semantic search functionality.

* Semantic Search: Perform a similarity search, also known as semantic search, on the vector database. This search will be based on the question you provide to GPT4All, serving as the context for generating the answer.

* Interact with GPT4All: Feed the question and context to GPT4All using Langchain. Wait for the model to process the input and provide the answer.

Please note that this process can be repeated with other models as well. Now let's delve into each step in more detail.

## Step-by-Step Guide
Step 1: Load the GPT4All Model
Download the GPT4All model from the official website. This model will be used as the backbone of our chatbot. Make sure to have it readily available for the subsequent steps.

Step 2: Use Langchain to Retrieve and Load Documents
Langchain is a powerful library that facilitates interaction with language models. Use Langchain to retrieve and load the documents you wish to include in your knowledge base. These documents can be in the form of PDFs or online articles.

Step 3: Split Documents into Embeddable Chunks
To process the documents effectively, split them into smaller chunks that can be digested by the embeddings module. This step ensures that the information in the documents is easily understandable by the subsequent components of the pipeline.

Step 4: Create a Vector Database with Embeddings using FAISS
Utilize FAISS, a library for similarity search and clustering, to create a vector database. This database will store the embeddings generated from the documents. It enables efficient and accurate semantic search functionality for our chatbot.

Step 5: Perform Semantic Search on the Vector Database
Perform a similarity search, also known as semantic search, on the vector database. This search is based on the question you want to pass to GPT4All and serves as the context for generating the answer. By leveraging the embeddings and FAISS, you can retrieve relevant information from the vector database.

Step 6: Interact with GPT4All using Langchain
Feed the question and the context to GPT4All using
## Demo
### Text Generation
![image](https://github.com/YaqoobD/GPT4All-on-CPU-Only/assets/52135942/4b88a2fa-f36d-48f5-b1b1-b45c98b2c1fb)

![image](https://github.com/YaqoobD/GPT4All-on-CPU-Only/assets/52135942/0f2c4fce-ca5a-4d0f-b128-e55b1a21346b)

### Text Generation Using LangChain Framework

![image](https://github.com/YaqoobD/GPT4All-on-CPU-Only/assets/52135942/84082722-8b0f-4d3f-af35-023b1c344cb5)

![image](https://github.com/YaqoobD/GPT4All-on-CPU-Only/assets/52135942/c77bbbc7-cbd8-4f2e-b6cd-b90ef73d5980)

