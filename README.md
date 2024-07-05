# Enhanced RAG (Retrieval Augmented Generation) with Re-Ranking

![Enhanced RAG](https://blogs.nvidia.com/wp-content/uploads/2023/11/Retrieval-Augmented-Generation-RAG-KV-1.jpg)

This repository contains an implementation of Enhanced Retrieval Augmented Generation (RAG) with a re-ranking mechanism using the CrossEncoder model. RAG combines retrieval and generation steps, making it possible to generate more accurate and relevant responses by leveraging a large corpus of documents. The re-ranking step further refines the retrieval process by prioritizing the most relevant documents.


## Features

- **Retrieval-Augmented Generation (RAG):**
  Combines retrieval of relevant documents and generation of coherent responses using state-of-the-art models.

- **Re-Ranking with CrossEncoder:**
  Improves retrieval results by re-ranking documents based on their relevance to the query using the CrossEncoder model.

- **Data Preprocessing:**
  Includes cleaning and preprocessing steps to remove unwanted characters and spaces from the retrieved documents, ensuring better quality input for the generation model.

## Workflow

- **Data Retrieval:**
  Retrieve relevant documents from a vector database based on a query.

- **Data Preprocessing:**
  Clean and preprocess the retrieved documents by removing backslashes and extra spaces.

- **Re-Ranking:**
  Use the CrossEncoder model to re-rank the retrieved documents, ensuring the most relevant documents are prioritized.

- **Response Generation:**
  Generate responses using the top-ranked documents to produce more accurate and contextually relevant answers.



#### Contributions are welcome! Please feel free to submit a Pull Request or open an Issue to improve the project.
