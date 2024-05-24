## Building Knowledge Graphs for Retrieval Augmented Generation (RAG) with Neo4j
-----------------------------------------------------------------------------

This repository contains notebooks for building knowledge graphs and using them to improve Retrieval Augmented Generation (RAG) systems. RAG leverages knowledge graphs with embedding models to enhance the quality of text retrieved for language models.

Here's a breakdown of the notebooks:

-   **Introduction to Knowledge Graphs**: These notebooks provide foundational knowledge about Knowledge Graphs, including their structure and advantages over traditional relational databases for data organization and retrieval. [1,2]
-   **Building a Knowledge Graph from SEC Filings**: These notebooks guide you through constructing a knowledge graph using Neo4j to represent data extracted from SEC filings. [3]
-   **Integrating Knowledge Graphs into RAG Systems**: These notebooks demonstrate how to integrate the constructed knowledge graph into a Retrieval Augmented Generation system using Langchain to retrieve relevant text passages for the language model. [3]
-   **Advanced Techniques (Optional)**: These notebooks (if included) delve deeper by building a second knowledge graph from another set of SEC filings. They then guide you through connecting these two graphs using linking data and demonstrate how to perform more intricate graph queries for RAG across multiple document sets. [4]

By completing these notebooks, you'll gain the ability to:

-   Grasp the core concepts of Knowledge Graphs.
-   Construct a knowledge graph from SEC filings using Neo4j.
-   Implement Knowledge Graphs to enhance Retrieval Augmented Generation systems.
-   Craft intricate graph queries to retrieve relevant information across extensive document collections (advanced notebooks).

This repository empowers you to develop RAG systems that retrieve more pertinent data for language models by incorporating Knowledge Graphs.