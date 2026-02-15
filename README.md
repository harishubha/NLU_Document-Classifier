# Text Document Classifier
This assignment presents the design and analysis of a binary text document classification system that classifies news articles into Sport or Politics categories. I have used the
BBC News dataset and compared three classical machine learning techniques: Naive Bayes, Logistic Regression, and Support Vector Machines (SVM). Multiple feature
representations including Bag of Words, TF-IDF, and N-grams were used. Quantitative results show all three ways of feature representations with Naive Bayes and TF-IDF
with bigrams combined with SVM achieves near-perfect accuracy.
####
Text classification is a fundamental Natural language processing (NLP) task that involves assigning predefined categories to text documents. In this assignment, designed a classifier that
distinguishes between Sport and Politics news articles using machine learning techniques.

The dataset used in this assignment is the BBC News Dataset obtained from Kaggle. The
dataset consists of news articles collected from the BBC website between 2004 and 2005. It
contains 2,225 news articles categorized into five topics: Business, Entertainment, Politics,
Sport, and Tech. For this task, only the Sport and Politics categories were filtered for use.
Source of which is the public data set on BBC news articles: D. Greene and P. Cunningham.
”Practical Solutions to the Problem of Diagonal Dominance in Kernel Document Clustering”,
Proc. ICML 2006. Original source: http://mlg.ucd.ie/datasets/bbc.html
A more refined version of this dataset (used for the assignment): https://www.kaggle.com/datasets/yufengdev/bbc-fulltext-and-category/data
