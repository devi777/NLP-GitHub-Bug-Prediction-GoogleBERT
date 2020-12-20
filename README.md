# NLP-GitHub-Bug-Prediction-GoogleBERT
Applying NLP techniques on Embold's github dataset and deploying Google's distilBERT model for classification.

# Overview
Developed a model using NLP (Python) with Google’s pretrained distilBERT .
The  dataset used has been taken from [MachineHack’s](https://www.machinehack.com/hackathons/predict_github_issues_embold_sponsored_hackathon/overview) Bug Prediction Dataset which was preprocessed using regex and NLTK python libraries. 

# Features
- feature extraction from raw text using TF-IDF, CountVectorizer
-	using word embeddings to represent words as vectors using Word2Vec, Gensim.
- visualizing Data using TSNE algorithm, Plotly-express' sunburst treemaps.
- optimizing accuracy score as a metric to generalize well on unseen data.
