# Movie Recommendation System — Semantic Similarity (NLP)

This project demonstrates a simple **content-based recommendation system** using **semantic similarity techniques** in natural language processing (NLP). Using movie plot descriptions, the system identifies which film a user is most likely to enjoy next based on textual meaning rather than explicit ratings or metadata.

The exercise focuses on **understanding and applying vector-based similarity**, rather than building a full-scale recommendation engine.

![Comic book image of the Incredible Hulk running towards you with a sword raised in his right hand. He appears to be on the surface of a small, barren planet or moon. His mouth is open as if he is screaming a battle cry.](Planet-Hulk.jpg)

<sub>Image source: https://www.bigglasgowcomicpage.com/review-planet-hulk/</sub>

---

## What’s in this repository

- **Jupyter Notebook:** semantic similarity implementation (`movies_task.ipynb`)  
- **Dataset:** movie plot descriptions (`movies.txt`)  
- **Requirements:** Python dependencies and spaCy language model (`requirements.txt`)  

---

## Project Context

Modern recommendation systems increasingly rely on understanding **semantic meaning** rather than surface-level keyword matching. Two movie descriptions may use different language while conveying similar themes, genres, or narrative structure.

This project explores how semantic similarity can be used to compare movie descriptions and recommend a title based purely on meaning, using pre-trained word embeddings.

---

## Approach Overview

The analysis follows a simple semantic similarity workflow:

- Load movie descriptions from a text file  
- Convert text into vector representations using spaCy  
- Compute similarity scores between descriptions  
- Identify the most semantically similar movie to *Planet Hulk*  

Recommendations are based on the **highest cosine similarity score** between text vectors.

---

## Key Insights / Findings

- Semantic similarity enables meaningful recommendations even when descriptions share few common words.  
- The spaCy medium-sized language model captures thematic and narrative relationships beyond keyword overlap.  
- Recommendation quality is strongly influenced by the quality of the underlying word embeddings.  
- This approach reflects the foundational logic behind many content-based recommendation systems.  

---

## Skills Demonstrated

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

## Requirements

Install the required Python packages with: `pip install -r requirements.txt`. *Note: this project also requires the spaCy language model *`en_core_web_md`.

---

## Why this project belongs in my portfolio
This project demonstrates my understanding of how semantic similarity can be applied to real-world recommendation problems. While intentionally small in scope, it highlights a core NLP concept that underpins modern systems used for content discovery, search relevance, and personalised recommendations, and complements my broader work in natural language processing.
