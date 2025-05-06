# arXiv-Analysis
## Topic Modelling + Sentiment Analysis of Research Papers in the arXiv Database
## Code is in file titled: project1.ipynb

![image](https://github.com/user-attachments/assets/c6e1d10f-c130-4d68-974c-86da6b160d06)
![image](https://github.com/user-attachments/assets/ceacc625-7072-42ac-ae05-1401f664a0b1)

## Goal: Automated topic analysis of 2.7M+ ArXiv papers using ML

## Pipeline
- Preprocessed text → Sentence-BERT embeddings → UMAP + K-Means (k=50)
- LLM-assisted labeling (Claude) for interpretable topics
- NetworkX cosine similarity (>0.7 threshold) to map topic relationships

## Key Insights
- Physics topics showed strong interconnections (high cosine similarity)
- Math topics remained distinct (low cross-topic similarity)
- Top growing fields: LLMs, quantum learning, telescope tech

## Technical Note
- Optimized k=50 clusters and cosine thresholds through iterative testing
