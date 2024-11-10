# Customer-Review-Sentiment-Analysis-with-NLTK

This project is focused on sentiment analysis of Amazon product reviews. The dataset contains review titles and the primary goal is to determine the sentiment behind each review (Positive, Negative, or Neutral). The workflow involves data preprocessing, tokenization, stopword removal, lemmatization, sentiment analysis, and visualization of results.

**Dataset**
The dataset consists of Amazon product reviews provided in an Excel file. Each review includes a short title or summary of the review text. This dataset is used to analyze the general sentiment and identify the most common words associated with each sentiment category.

**Project Workflow**
*1. Data Loading and Exploration*
Library: pandas
The dataset is loaded and initially explored to understand its structure and content.

*2. Data Preprocessing*
Tokenization: Each review title is tokenized to create a list of words.
Stopword Removal: Common English stopwords are removed from the tokenized words using NLTK's predefined stopwords list.
Lemmatization: Remaining tokens are lemmatized to obtain the root form of each word.

*3. Sentiment Analysis*
VADER Sentiment Analyzer: VADER (Valence Aware Dictionary for Sentiment Reasoning) is used to score the sentiment of each review title.
Sentiment Labeling: Based on the compound sentiment score, each review is labeled as "Positive," "Negative," or "Neutral."

*4. Visualization*
A bar chart is generated to display the distribution of sentiments (Positive, Negative, Neutral) among the reviews.

*5. Word Frequency Analysis*
Word frequency is analyzed within each sentiment category to identify common words in positive, negative, and neutral reviews.

**Packages Used**
pandas: Data manipulation and handling.
nltk: Tokenization, stopword removal, lemmatization, and sentiment analysis (VADER).
matplotlib: Visualization of sentiment distribution.
