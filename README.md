# Retrieval Augmented Generation(RAG)

[বাংলা সংস্করণ পড়ুন](./README.bn.md)

### What is RAG (Retrieval-Augmented Generation)?
RAG (Retrieval-Augmented Generation) is a hybrid model that combines two key components:

- Information retrieval (fetching relevant documents or passages from a large dataset)
- Text generation (using a language model to generate coherent responses).
  
The key idea behind RAG is to improve the accuracy and relevance of language models by allowing them to retrieve supporting information during inference, instead of relying solely on the data seen during training. This is especially helpful for answering questions that require up-to-date or domain-specific knowledge.

##### Example:
Imagine you ask a RAG-based model, “What are the latest trends in AI?”

1. The model first retrieves documents or paragraphs related to recent AI trends from a knowledge base (e.g., a collection of news articles or research papers).
2. Then, it generates a response by summarizing the retrieved documents in the context of your query.

![Rag diagram](assets/Diagram.png)
