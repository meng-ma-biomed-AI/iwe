# RadiologyReportEmbedding

A hybrid strategy that combines semantic-dictionary mapping and word2vec modeling, has been applied to create the word embeddings from 10,000 CT Head radiology report.  

We followed the following step: Data set retrieval from PACS, Data Cleaning & Pre-processing, Semantic-dictionary mapping (CLEVER and RadLex terminology), and Word and Report Embedding via Continuous Bag Od Word model. The size of the resulting vocabulary was 4,442 words.

Using the vector representation, we automatically classify them into three classes denoting the confidence in the diagnosis of intracranial hemorrhage by the interpreting radiologist. We performed a range of experiments with different classifiers and varying hyper-parameters settings. Best performance achieved is weighted precision of 88% and weighted recall of 90%. 

The Radiology word vectors can be resued in similar classification scenarios or can be used to interpret word-to-word relations.
