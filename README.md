# Traditional-DS---Spam-Ham-Detection

•	Clear task definition and high-quality labels
Each email is explicitly labeled as spam or ham, with no ambiguity or multi-label complexity. This allows focus on modeling and feature engineering rather than data annotation.

•	Moderate size for systematic experimentation
With ~5,000 samples, the dataset supports cross-validation and hyperparameter tuning (e.g., grid search) across models such as Naive Bayes, Logistic Regression, SVM, and Random Forest, without excessive computational cost.

•	Simple structure with realistic content
The dataset has a clean format but includes realistic noise (e.g., HTML tags, forwarded content, headers), providing a practical setting for text preprocessing and feature extraction.

•	Moderate class imbalance
The class distribution (≈71% ham, 29% spam) introduces moderate imbalance. This allows meaningful discussion of evaluation metrics beyond accuracy (e.g., Precision, Recall, F1-score), as well as techniques such as class weighting.

•	Strong real-world relevance and literature support
Spam detection is a well-studied problem with extensive literature and benchmarks. This enables comparison with established methods and contextualization of results.

•	Suitable for end-to-end machine learning workflow
The dataset supports a complete pipeline, including: 

Exploratory Data Analysis (EDA) and visualization, Feature engineering (Bag-of-Words, TF-IDF, n-grams, stopword removal), Model comparison (e.g., MultinomialNB, Logistic Regression, Linear SVM, Random Forest), Hyperparameter tuning and imbalance handling, Model interpretation (e.g., feature importance, confusion matrix analysis)

