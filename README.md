GraphRAG is an advanced version of Retrieval-Augmented Generation (RAG) that improves LLM performance by using knowledge graphs instead of basic text snippet retrieval. It works by extracting a knowledge graph from raw text, clustering it hierarchically, and summarizing these clusters for better reasoning. The process involves three main steps:

1. **Indexing**: Splitting the text into units, extracting entities and relationships, and creating a hierarchical graph.
2. **Querying**: Using the knowledge graph for global, local, or DRIFT search to enhance the model's understanding of complex information.
3. **Prompt Tuning**: Fine-tuning prompts to improve results when working with specific datasets.

GraphRAG helps overcome limitations of baseline RAG, especially in understanding large, complex data and connecting disparate information effectively.
