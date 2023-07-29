# BERT v.s. Gzip+kNN v.s. LGBM
I want to try to use a language model to solve tabular classification problems which are usually used some regular machine learning models such as logistic regression or random forest. 
The data I use is from Kaggle [Latest Data Science Salaries](https://www.kaggle.com/datasets/iamsouravbanerjee/data-science-salaries-2023)
The model competitors are: 
1. Pre-trained BERT: BertwithTabular
2. LGBM Regressor: CompressionClassification
3. Gzip + kNN: CompressionClassification

Gzip + kNN is from this paper [“Low-Resource” Text Classification: A Parameter-Free Classification Method with Compressors](https://aclanthology.org/2023.findings-acl.426.pdf)
The original code is [here](https://github.com/bazingagin/npc_gzip).
I write an article to explain it: [Gzip + kNN: A Good Text Classifier?](https://chengchinglin.coderbridge.io/2023/07/28/gzip-knn/). Here, I just use the code they type in the paper.
