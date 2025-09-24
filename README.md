🏋️ Fitness Brand Sentiment Analysis

This project analyzes how people feel about major fitness brands using Reddit comments.
By applying data cleaning, lemmatization, and machine learning sentiment analysis, the project uncovers marketing insights about brand perception.

📂 Project Overview

Data Source: ~58,000 Reddit posts and comments mentioning brands like:

Planet Fitness

Peloton

Gold’s Gym

Anytime Fitness

Nike Training Club

Objective:

Clean and preprocess raw social media text.

Apply NLP techniques to classify sentiment (positive, neutral, negative).

Compare sentiment distribution across different brands.

Visualize insights for marketing strategy.

🛠️ Techniques Used

Data Cleaning

Removed links, special characters, and duplicates.

Lowercased and normalized text.

Lemmatization

Reduced words to dictionary form (e.g., running → run).

Used NLTK’s WordNetLemmatizer with POS tagging.

Sentiment Bootstrapping

Used VADER Sentiment Analyzer to generate initial labels (positive/neutral/negative).

Machine Learning Classifier

Converted text into numerical features with TF-IDF.

Trained a Logistic Regression classifier.

Achieved ~84% accuracy.

Visualization

Stacked bar charts for brand sentiment.

Word clouds for positive and negative words.

Sentiment vs. upvote score analysis.

📊 Key Insights

Nike Training Club had the highest positive sentiment (63%).

Planet Fitness showed the highest negativity (29%).

Peloton & Anytime Fitness were moderately positive (~52%).

Gold’s Gym was more balanced, with many neutral comments.

👉 Positive themes: love, good, work, gym, time
👉 Negative themes: pay, cancel, stop, bad, stupid

📦 Installation & Setup
1. Clone this repo
git clone https://github.com/yourusername/fitness-brand-sentiment.git
cd fitness-brand-sentiment

2. Install dependencies
pip install -r requirements.txt

3. Run the notebook/script

If using Jupyter Notebook:

jupyter notebook sentiment_analysis.ipynb


Or as a Python script:

python sentiment_analysis.py

📈 Example Outputs

Brand sentiment distribution chart

Positive/Negative word clouds

Classification report + confusion matrix
