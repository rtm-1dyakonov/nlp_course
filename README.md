# Movie Genre Prediction by Its Synopsis
This document is the report for NLP course project and will provide you insights about different ways to classify movies as either comedies or dramas based on their synopsis.

# Datasets
Wikipedia Movie Plots : https://www.kaggle.com/datasets/jrobischon/wikipedia-movie-plots

News Category Dataset : https://huggingface.co/datasets/khalidalt/HuffPost/blob/main/News_Category_Dataset_v2.json

GloVE 6B 100d : https://www.kaggle.com/datasets/rtatman/glove-global-vectors-for-word-representation

# Research
All stages of the work are outlined in *Movie genre prediction (comedy and drama) by its synopsis.pdf*. Python notebook *nlp_course_code.ipynb* includes data preprocessing, models' architectures and final outcomes. 

# Models
Tokenizer -> GloVE embedings -> CNN 3 layers / LSTM-CNN 3 layers -> Ensemble

# Metrics
The highest accuracy score achieved is 0,692. 

# Authors
Artem Razdyakonov S42012
