# Reddit-Sentimental-analysis

Objective: This notebook performs sentiment analysis, keyword extraction, and issue/product identification on Reddit comments related to Corsair products.

Key Tasks:
Sentiment Analysis: Using VaderSentiment, comments are classified as positive, negative, or neutral.
Keyword Extraction: Keywords are extracted from comments using the YAKE library.
Issue Identification: Negative comments are analyzed to identify specific issues (e.g., hardware failure, performance issues) using a combination of fuzzy matching and word2vec similarity.
Product Identification: Products mentioned in the comments are identified using regex and a predefined list of Corsair products.
Data Visualization: The sentiment distribution is plotted using Matplotlib.
Developed a sentiment analysis pipeline using machine learning models (Logistic Regression, Random Forest, SVM, Naive Bayes) to classify Reddit comments, achieving 73.68% accuracy with Logistic Regression.

Utilized NLP techniques (VaderSentiment, YAKE, RapidFuzz, Word2Vec) for sentiment analysis, keyword extraction, and issue/product identification from customer feedback.

Automated the identification of product-related issues and categorized them into predefined categories (e.g., hardware failure, performance issues).

Visualized sentiment distribution using Matplotlib and saved analyzed data to CSV for further insights.

Tools: Python, Scikit-learn, Pandas, Gensim, YAKE, VaderSentiment.
