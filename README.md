# BA-Review-Analysis

Project Overview

This project involves scraping the data from the website, cleaning, analyzing, and visualizing British Airways customer reviews from AirlineQuality.com. The analysis focuses on sentiment distribution, topic modeling, and word cloud visualization to extract insights from customer feedback.

Dataset

BA_reviews.csv: Raw dataset containing scraped reviews.

BA_reviews_cleaned.csv: Processed dataset with cleaned text for analysis.

data_scraping.ipynb: Jupyter Notebook containing the web scraping script.

BA_Review_Insights.pptx: Final PowerPoint slide summarizing key findings.

Key Features

1. Web Scraping

Extracted reviews using requests and BeautifulSoup.

Stored data in a structured CSV file.

2. Data Cleaning & Preprocessing

Removed special characters, stopwords, and unnecessary text.

Used tokenization and lemmatization for better analysis.

3. Sentiment Analysis

Analyzed sentiment polarity using TextBlob.

Classified reviews as Positive, Negative, or Neutral.

4. Topic Modeling (LDA)

Applied Latent Dirichlet Allocation (LDA) for topic extraction.

Identified key topics: Flight experience, Customer service, Seat comfort, and Food quality.

5. Data Visualization

Pie chart for sentiment distribution.

Word cloud to highlight frequently mentioned words.

PowerPoint slide summarizing key insights.

Results Summary

✅ Sentiment Distribution:

619 Positive, 364 Negative, 17 Neutral reviews.

Majority of reviews express either strong satisfaction or dissatisfaction.

✅ Key Topics:

Flight experience, Customer service, Seat comfort, Food quality are the most discussed.

✅ Most Frequent Words:

Displayed using a word cloud to highlight key themes.

Technologies Used

Python: Data processing & analysis

Libraries: requests, BeautifulSoup, pandas, nltk, textblob, wordcloud, matplotlib, sklearn, pptx

Jupyter Notebook for implementation

PowerPoint for final presentation

How to Use

Clone the repository:

git clone https://github.com/your-username/BA_Review_Analysis.git
cd BA_Review_Analysis

Install dependencies:

pip install -r requirements.txt

Run the notebook to scrape and analyze the data:

jupyter notebook data_scraping.ipynb

Review the results in BA_Review_Insights.pptx.

Future Improvements

Expand to other airlines for comparative analysis.

Improve sentiment accuracy with advanced NLP models.

Add customer recommendations for service improvements.

Author

[Your Name] - [Your GitHub Profile]

This project is a part of my data science portfolio showcasing web scraping, NLP, and data visualization skills.
