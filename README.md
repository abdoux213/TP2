# Retrieval-Augmented Generation (RAG) pour Cours de Business Intelligence

Ce projet implémente un système **RAG (Retrieval-Augmented Generation)** qui permet de poser des questions intelligentes sur des documents PDF, en utilisant LangChain, ChromaDB et OpenAI.

Il est particulièrement adapté au cours de **Business Intelligence (BI)** fourni dans `pdfs/BI_Cours.pdf`, mais il est facilement extensible à d'autres documents.

## Fonctionnalités
- Chargement et indexation de PDFs.
- Découpage intelligent du texte en chunks.
- Stockage vectoriel avec **ChromaDB** (persistant).
- Recherche sémantique des passages pertinents.
- Génération de réponses "groundées" (basées uniquement sur le contexte du document).
- Interface expérimentale via Jupyter Notebook.
- Chatbot web via **Streamlit**.
- Évaluation automatique de la fidélité des réponses.

## Technologies utilisées
- **Python 3.13+**
- **LangChain** + LangChain Community
- **ChromaDB** (vector store)
- **OpenAI** (embeddings `text-embedding-ada-002` + modèles GPT)
- **Streamlit** (interface web)
- **PyPDF** (lecture des PDFs)

## Installation

1. Clone le repository (ou décompresse le ZIP) :
   ```bash
   git clone <url-du-repo>
   cd retirieval-augmented-generation
