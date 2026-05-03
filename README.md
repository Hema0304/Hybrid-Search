**Hybrid Search Engine (Semantic + Keyword)**

This project implements a Hybrid Search Engine that combines both semantic search (vector-based) and keyword search (traditional text-based) to deliver more accurate and context-aware results.

Unlike standard search systems that rely only on exact keyword matching, this system understands the meaning of queries while also preserving the precision of keyword search.
Hybrid search systems often combine vector similarity with structured filtering, improving both relevance and flexibility

## Features

Combined semantic + keyword search

Improved search accuracy over traditional methods

Context-aware query understanding

Ranking and merging of results

Handles both structured and unstructured data

Suitable for RAG (Retrieval-Augmented Generation) systems

## Tech Stack

Python

LangChain / LLM frameworks

Vector embeddings

FAISS / Chroma / similar vector database

Keyword search

## How It Works

Convert documents into embeddings (vector representation)

Store embeddings in a vector database

Perform keyword-based search on text data

Perform semantic (vector) search

Combine both results using ranking/weighting

Return the most relevant results

🔥 Novelty of the Project

Combines two powerful retrieval techniques

Handles both exact match and contextual meaning

Improves performance for real-world search applications

Can be extended to chatbots and AI assistants

## Future Enhancements

Add reranking models for better relevance

Implement dynamic weighting between search types

Integrate with large-scale vector databases

Build UI using Streamlit

Deploy as a web-based search engine

## Conclusion

This project demonstrates how combining semantic understanding with keyword precision can significantly improve search quality. Hybrid search is a key technique used in modern AI-powered applications and forms the backbone of many advanced retrieval systems.
