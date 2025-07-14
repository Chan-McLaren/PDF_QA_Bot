# PDF_QA_Bot
RAG Chatbot – PDF Question Answering 
Built with IBM Watsonx + LangChain | IBM Generative AI Engineering Certification Project

This project is a Retrieval-Augmented Generation (RAG) chatbot that lets you upload a PDF file and ask questions about its content. It was developed as part of my Generative AI Engineering Certificate using IBM Watsonx foundation models, LangChain, and Gradio.

How It Works:

1. Upload a PDF file in the Gradio web interface.

2. The PDF is parsed and split into text chunks.

3. Each chunk is embedded using IBM Watsonx Embeddings (ibm/slate-125m-english-rtrvr).

4. The chunks are stored in a Chroma vector database.

5. When you ask a question, relevant chunks are retrieved.

6. An answer is generated using the Watsonx LLM (mistralai/mixtral-8x7b-instruct-v01).

7. The result is then returned in the interface as a natural language response.
