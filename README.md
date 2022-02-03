# Semantic clustering of UM6P research papers

Back with a new post, This time I want to share with you an  application of text embedding (a popular NLP technique).
By embedding the abstract of +900 paper affiliated to UM6P, we can extract  contextual clusters of papers that describe the landscape of research in UM6P in terms of topics and subfields. 

This new representation help enrich the existing research papers by giving them tags and a personalized classification that go beyond the standardized and high level  taxonomies used to structure the research corpus. 

# Tools 
- [SentenceTransformers](https://www.sbert.net/) : Doc embedding
- [UMAP](https://umap-learn.readthedocs.io/en/latest/) : dimension reduction 
- [DBSCAN](https://github.com/wangyiqiu/dbscan-python) : clustering 
