# [**Large Language Models with Semantic Search** ](https://www.deeplearning.ai/short-courses/large-language-models-semantic-search/) 

## **Overview**  
This repository contains course notes and Jupyter notebooks for the **Large Language Models with Semantic Search** course. The course explores **semantic search techniques** and how to integrate **Large Language Models (LLMs)** to improve search accuracy and relevance.  

### **What You'll Learn**  
- Implement **basic keyword search**, the foundation of many search systems.  
- Enhance search results using **Cohere Rerank**, which prioritizes relevant responses.  
- Use **embeddings for dense retrieval**, leveraging semantic meaning to improve search accuracy.  
- Evaluate search effectiveness using **Mean Average Precision (MAP)**, **Mean Reciprocal Rank (MRR)**, and **Normalized Discounted Cumulative Gain (NDCG)**.  
- Build **semantic search from scratch** using **vector databases** and **approximate nearest-neighbor (ANN) search**.  
- Integrate **LLM-powered search** into real-world applications.  

---

## **Course Content**  

### [**1. Keyword Search** ](https://github.com/michaWorku/LLMs_with_Semantic_Search/tree/main/L1_Keyword_Search) 
- Set up a **Weaviate** client for search queries.  
- Define a **keyword search function** with query parameters.  
- Perform keyword-based search and analyze the results.  
- Modify query options to improve search quality.  

### [**2. Embeddings**](https://github.com/michaWorku/LLMs_with_Semantic_Search/tree/main/L2_Embeddings)  
- Load API keys and relevant Python libraries (**Cohere, UMAP, Altair, Datasets**).  
- Create word, sentence, and article embeddings.  
- Use embeddings to represent text in a dense vector space.  

### [**3. Dense Retrieval**](https://github.com/michaWorku/LLMs_with_Semantic_Search/tree/main/L3-Dense_Retrival)  
- Load API keys and set up **Weaviate** and **Annoy** for search.  
- Implement **vector-based semantic search** with dense retrieval.  
- Compare **keyword search vs. dense retrieval** for different query complexities.  
- Build a **semantic search system from scratch**:  
  - Text preprocessing and chunking.  
  - Creating embeddings for text.  
  - Indexing and retrieving relevant results.  

#### **ANN vs. Vector Databases**  
- **Approximate Nearest-Neighbor (ANN) search** using libraries like **Annoy, FAISS, ScaNN**.  
- **Vector databases** (Weaviate, Pinecone, PostgreSQL, Chroma) for storing and querying both vectors and text.  

### [**4. Rerank**](https://github.com/michaWorku/LLMs_with_Semantic_Search/tree/main/L4-ReRank)  
- Improve search relevance by **reranking keyword search and dense retrieval results** using **Cohere Rerank**.  
- Evaluate search performance using **MAP, MRR, and NDCG metrics**.  

### [**5. Generating Answers**](https://github.com/michaWorku/LLMs_with_Semantic_Search/tree/main/L5-Generative_Search)  
- Build an **LLM-powered answer generation system**:  
  - **Chunk** and clean text data.  
  - **Embed** documents for semantic search.  
  - **Search articles** using vector similarity.  
  - **Generate responses** by retrieving relevant content and crafting an LLM prompt.  

---

## **Getting Started**  
The notebooks provide **hands-on experience** in implementing and optimizing **LLM-powered search systems**. Start by exploring keyword search, then progress to embeddings, dense retrieval, reranking, and answer generation.  

🚀 **By the end of this course, you'll be able to build advanced search applications that go beyond keyword matching!**
