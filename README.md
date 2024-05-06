# Local LLMs, Few-Shot Prompting, and RAG QA: A Practical Guide

This repository contains three Jupyter notebooks that demonstrate the use of local Large Language Models (LLMs), few-shot prompting techniques, and Retrieval Augmented Generation (RAG) for question answering. Each notebook is designed to provide practical insights into different aspects of working with LLMs.

## Notebooks Overview

### 1. **Local Models vLLM**

This notebook introduces the basics of setting up and running local LLMs for various NLP tasks such as translation, summarization, and entity extraction without relying on external API services. It utilizes open-source libraries like `vLLM` and `LangChain` to handle model inference and application development.

- **Key Features:**
  - Installation and setup of `vLLM` and `LangChain`.
  - Initialization and interaction with a local LLM.
  - Practical examples of prompt engineering and templating for effective model querying.

### 2. **Few-Shot Prompting**

Explores the concepts of zero-shot, one-shot, and few-shot learning. This notebook demonstrates how to adapt LLMs to new tasks with minimal examples, enhancing their ability to make predictions or classifications based on limited input.

- **Key Features:**
  - Implementation of zero-shot and few-shot learning paradigms.
  - Setup of classification tasks using structured prompting.
  - Batch processing for handling multiple inputs efficiently.

### 3. **Local RAG QA**

Focuses on Retrieval Augmented Generation for question answering by integrating document retrieval into the response generation process. It uses tools like `PyPDFLoader`, `HuggingFaceEmbeddings`, and `Chroma` for document handling and embedding.

- **Key Features:**
  - Extraction and vectorization of text data from PDF documents.
  - Setup of a retrieval system to fetch relevant context for question answering.
  - Integration of RAG with local LLMs to generate responses based on retrieved information.

## Installation

To run the notebooks, you need to install the required libraries. You can do this by executing the following commands in your Jupyter notebook:

```bash
%pip install --upgrade vllm -q
%pip install langchain langchain_community -q
%pip install pypdf sentence-transformers chromadb -q
```

## Usage

Open the Jupyter notebooks in an environment that supports Python (e.g., Google Colab, Jupyter Lab). Ensure you have access to a GPU for optimal performance, especially when working with large models.

## Contributing

Contributions to improve the notebooks or extend the functionalities are welcome. Please feel free to fork the repository, make changes, and submit a pull request.

## License

This project is open-sourced under the MIT license. See the LICENSE file for more details.