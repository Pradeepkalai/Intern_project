# Intern Project

---

## Day 1: Text Normalization, Tokenization & Stopword Removal using NLTK


### Overview

This project demonstrates fundamental **Natural Language Processing (NLP)** preprocessing techniques using **Python** and **NLTK**.

### Features

- **Text Normalization** – Converts text to lowercase.
- **Tokenization** – Splits text into individual words.
- **Stopword Removal** – Removes common English stopwords to retain meaningful words.


### Technologies Used

| Technology | Purpose |
|------------|----------|
| Python 3.x | Programming Language |
| NLTK | Natural Language Processing Library |


### Installation

Install NLTK using the following command:

```bash
pip install nltk
```


### Required NLTK Resources

The following resources are downloaded automatically when the program runs:

```python
nltk.download('punkt')
nltk.download('punkt_tab')
nltk.download('stopwords')
```

---


## Day 2: Building a Document Embedding Pipeline with PyPDF2, LangChain & Hugging Face


### Overview

This project demonstrates how to extract text from PDF documents, split the content into manageable chunks, and generate vector embeddings using **Hugging Face Sentence Transformers**. These embeddings enable intelligent document understanding and form the foundation of modern AI applications such as **Semantic Search**, **RAG (Retrieval-Augmented Generation)**, and **Question Answering Systems**.

### Features

- **PDF Loading** – Reads PDF documents efficiently.
- **Text Extraction** – Extracts textual content from PDF files.
- **Text Chunking** – Splits large documents into smaller chunks.
- **Embedding Generation** – Converts text chunks into vector embeddings.
- **Embedding Analysis** – Displays the shape and structure of generated embeddings.

### Required Libraries

| Library | Purpose |
|----------|----------|
| PyPDF2 | Extracts text from PDF documents |
| langchain | Framework for building LLM applications |
| langchain-community | Community integrations for LangChain |
| langchain-text-splitters | Splits large text into smaller chunks |
| sentence-transformers | Generates text embeddings |
| transformers | Provides Hugging Face transformer models |
| torch | Backend for deep learning and model execution |

### Technologies Used

| Technology | Purpose |
|------------|----------|
| Python 3.x | Programming Language |
| PyPDF2 | PDF Processing |
| LangChain | Document Processing Framework |
| Hugging Face | Embedding Models |
| Sentence Transformers | Text Embedding Generation |
| PyTorch | Deep Learning Backend |


### Installation

Install the required libraries using the following commands:

```bash
pip install PyPDF2
pip install langchain
pip install langchain-community
pip install langchain-text-splitters
pip install sentence-transformers
pip install transformers
pip install torch
```


### Embedding Model Used

```text
thuan9889/llama_embedding_model_v1
```

This Hugging Face model is used to convert document text into high-dimensional numerical vectors that capture semantic meaning.

---


