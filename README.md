# PDF-AI
This Python application facilitates loading a PDF document and querying it using natural language. It employs a Language Model (LLM) to formulate responses based on the PDF content. The LLM is designed to refrain from answering questions not pertinent to the document. The application processes the PDF by segmenting its text into smaller sections, which are subsequently inputted into the LLM. Utilizing OpenAI embeddings, the application generates vector representations of these sections. Subsequently, it identifies text segments semantically related to the user's query and forwards them to the LLM to produce a response.
#  Installation 

1. Clone the repo

 ```
 git clone https://github.com/KalyanMurapaka45/DocGenius-Revolutionizing-PDFs-with-AI.git
 ```
 
 2. Install the required libraries

```
pip install -r requirements.txt
```

```You will also need to add your OpenAI API key to the .env file.```

3. To use the application, run the ```app.py``` file with the streamlit CLI (after having installed streamlit):

```
streamlit run app.py
```
