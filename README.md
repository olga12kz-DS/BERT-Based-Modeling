# BERTopic:  Topic Modeling with Bidirectional Encoder Representations from Transformers (BERT)

BERTopic is a Machine Learning framework that leverages transformers, whose architecture is effective at capturing contextual relationships in large volumes of unstructured text. One of the powerful applications of transformer-based models is topic modeling — unsupervised clustering of textual data into learned, semantically meaningful topics. BERTopic combines contextual embeddings, dimensionality reduction, and clustering into a cohesive pipeline. As such, BERTopic is particularly well-suited for clinical text, which is often complex (a pinnacle of professional jargon!). 

In this example, the first step — generating fixed contextual embeddings for tokens across 2,000 clinical notes on the pre-trained bio_clinicalBERT model — has been completed and saved for future analysis in a .csv file. These embeddings form the foundation for downstream semantic analysis. 

The results can be used for topic modeling and text summarizations for:
- Discharge planning.
- Care quality assurance and compliance. 
- Population Health initiatives. 

***Please note that due to human subject research regulations, the MIMIC-III dataset cannot be publicly shared. I invite you to review the enclosed code and slides to explore the project further.
