# Knowledge Graph-based Evaluation Framework for RAG Systems 
This repository provides an **evaluation framework** for Retrieval-Augmented Generation (RAG) systems based on **knowledge graphs (KGs)**. It aims to offer a **structured and interpretable** way to assess RAG pipelines beyond traditional IR and NLP metrics.
## ✨ Features
- **Knowledge Graph Construction**: Build entity–relation graphs from both retrieved documents and generated outputs.
- **Entity & Relation Alignment**: Compare the consistency between retrieved evidence and generated responses at the KG level.
- **Evaluation Metrics**:
  - **Multi-hop Semantic Matching**: Assess whether the generated response preserves reasoning chains across multiple hops in the KG.
  - **Community-based Semantic Overlap**: Evaluate how well entities and relations in the output align with semantic communities in the KG.
  - **Sensitivity to Subtle Semantics**: Detect fine-grained semantic differences that traditional metrics may overlook.
- **Extensible**: Easily integrate with existing RAG implementations.
## 📂 Project Structure
- **RAGAS Evaluation**: Integration of the RAGAS framework for baseline comparison.  
- **Custom Evaluation**: KG-based evaluation metrics (Multi-hop Semantic Matching, Community-based Semantic Overlap, sensitivity).  
- **RAG System Implementation**: Example pipeline to demonstrate end-to-end RAG workflows.  
- **Webpage Extractor**: Utility for extracting and preprocessing content from webpages as RAG Knowledge.  


