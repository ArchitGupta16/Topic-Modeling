# Topic-Modeling
Developed a hybrid model by introducing summarization in the pipeline, to extract relevant content from the document. The T5 generated summaries were transformed into embedding vectors using BERT. The generated embeddings were dimensionally reduced using UMAP which was then clustered using DBSCAN. The final topic representation was given to the clusters via TF-IDF. 
![Summary Model Flowchart](https://github.com/ArchitGupta16/Topic-Modeling/assets/80447128/9ef318a0-7a25-4edc-bf6c-8e0cfe779124)
