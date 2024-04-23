# GenreProphet

### Description
This project analyzes Biblical text to study relationships in the text. Specifically, it focuses on using verses to predict their genres and authors.

The project is structured as follows:
1. Data cleaning
2. Exploratory data analysis
3. Embed verses, tagged by genre, using Doc2Vec
4. Predict verse genre using Logistic Regression
5. Hyperparameter tuning of vector_size
6. Analyze misclassifications
7. Cluster verses and analyze clsuter-genre relationships
8. Repeat steps 3-7 for verse author

#### Dataset
The data used in this project is accessed directly from [Demo Dataverse](demo.Dataverse.org). However, the data were originally sourced from [Kaggle](https://www.kaggle.com/datasets/oswinrh/bible) and [GitHub](https://github.com/happygrammer/bible-metadata).

### Usage
To run this project, the user must simply install the follow dependencies: scikit-learn, gensim, matplotlib, pandas, wordcloud, nltk, seaborn. For more a description of the main components of this project, word embedding and machine learning, visit the documentation: [Doc2Vec](https://radimrehurek.com/gensim/models/doc2vec.html) and [scikit-learn](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html).
