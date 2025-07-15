# AG_News_Text_Classification
# Project Overview
Objective: Classify AG News articles into 4 categories.
Categories: World, Sports, Business, Science
Techniques: Machine Learning & Deep Learning
Tools: Python, NLTK, Pandas, Seaborn, WordCloud

# Dataset Description
Format: CSV with columns - index, title, description
Merged 'title' and 'description' into a single text column
Class mapping: 1-World, 2-Sports, 3-Business, 4-Science

# Data Preprocessing
#### Text Cleaning:
Lowercasing, punctuation & stopword removal
Lemmatization and contraction expansion
Special character filtering
Generated WordClouds for frequent words visualization

# Exploratory Data Analysis
Analyzed class distribution across categories
Plotted word frequencies for each class
Used seaborn and matplotlib for visualization
Visual inspection through word clouds

# Modeling Approach
Text Tokenization and Padding
Implemented multiple models
Traditional ML models (notebook likely includes)
Deep Learning models (e.g., RNNs or CNNs)
Evaluation on test dataset

# Results and Evaluation
Metrics: Accuracy, Precision, Recall, F1-Score
Performance compared across models
Visualized results (e.g., confusion matrix, accuracy curves)
Selected best performing model

# Conclusion
Effective text classification achieved using NLP techniques
Word clouds and EDA gave good insights into data
Models showed strong performance on test set
Preprocessing and tokenization significantly impacted accuracy

# Future Work
Try transformer models like BERT or RoBERTa
Hyperparameter tuning for DL models
Experiment with data augmentation for text
Deploy model as a web app or REST API








