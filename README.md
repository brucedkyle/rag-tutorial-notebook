# RAG Tutorial

This is a demonstration of a simple Retrieval Augmented Generation (RAG) system, designed to answer user queries based on information extracted from a provided text file.

This is meant to be provide an overview of the steps to understand how RAGs work and how you can identify issues in your development early.

## Notebooks

There are two notebooks:

- [RAG in eight lines](./rag-in-eight-lines.ipynb) shows how vectors are used to select the documents that we have in our RAG.
- [Naive RAG](./naive_rag.ipynb) an end to end tutorial of RAG where you:
  
  1. Bring in content from selected websites
  2. Create the embeddings
  3. Store those embeddings
  4. Pose a question and retrieve documents using those embeddings
  5. Use a large language model to take the documents and provide a response to the user
 
Notebooks are stand-alone, meaning you can run them locally or in Colab. [requirements.txt](./requirements.txt] is provided as the list of packages used in the notebooks, but not required to run the notebooks.

## Presentation

- PowerPoint [Intro to RAG.with Demo.pptx](./presentation/Intro to RAG.with Demo.pptx)

## Prerequisites

- [Hugging Face API key](https://huggingface.co/docs/hub/security-tokens)
- Optionally: Colab account running a L4 (requires a subscription)

Skills

- How to navigate and run Jupyter Notebooks
- How to run your notebook in Colab
