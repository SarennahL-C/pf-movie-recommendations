# Movie Recommendation System — Semantic Similarity (NLP)

This project demonstrates a simple **content-based recommendation system** using **semantic similarity techniques** in natural language processing (NLP). Using movie plot descriptions, the system identifies which film a user is most likely to enjoy next based on textual meaning rather than explicit ratings or metadata. The exercise focuses on **understanding and applying vector-based similarity**, rather than building a full-scale recommender engine.

![Comic book image of the Incredible Hulk running towards you with a sword raised in his right hand. He appears to be on the surface of a small, barren planet or moon. His mouth is open as if he is screaming a battle cry.](Planet-Hulk.jpg)

*Image source: https://www.bigglasgowcomicpage.com/review-planet-hulk/*

---

### What’s in this repository

- **Notebook:** semantic similarity implementation (`movies_task.ipynb`)  
- **Dataset:** movie descriptions (`movies.txt`)  
- **Requirements:** spaCy language model and Python dependencies (`requirements.txt`)

---

### Project Context

Modern recommendation systems often rely on understanding *semantic meaning* rather than surface-level keyword matching. Two movie descriptions may use different words while conveying similar themes, genres, or narrative structure. In this task, semantic similarity is used to compare movie descriptions and recommend the most similar title based on meaning alone.

---

### Approach Overview

- Load a list of movie descriptions from a text file  
- Use spaCy’s medium-sized language model (`en_core_web_md`)  
- Convert descriptions into vector representations  
- Compute similarity scores between descriptions  
- Identify the most semantically similar movie to *Planet Hulk*  

The recommendation is based on the **highest cosine similarity score** between vectors.

---

### Key Insights / Findings

- Semantic similarity allows recommendations even when descriptions share few common words.  
- The medium-sized spaCy model captures thematic relationships such as genre and narrative structure.  
- Results depend heavily on the quality of the underlying word embeddings.  
- This approach mirrors the foundational logic behind content-based recommendation systems.  

---

### Skills Demonstrated

**Analysis**
- Interpretation of semantic similarity scores  

**Modelling**
- Vector-based text representation  
- Sentence-level similarity comparison  

**Tools**
- Python  
- spaCy (`en_core_web_md`)  
- Natural language processing fundamentals  

---

### Requirements / How to Run

Install dependencies and the required language model using `requirements.txt`

---

### Why this project belongs in my portfolio
This project demonstrates my understanding of how semantic similarity can be applied to real-world recommendation problems. While intentionally small in scope, it highlights a key NLP concept that underpins many modern systems used for content discovery, search relevance, and personalised recommendations.
