iPhone 15 128GB Sentiment Analysis This project performs sentiment analysis on customer reviews for the iPhone 15 128GB model on Flipkart. By scraping reviews, analyzing sentiments, and deriving insights, this project aims to evaluate the overall public perception of the product and suggest actionable improvements.

Overview In this project, we:

Scraped customer reviews from Amazon’s product page.

Preprocessed the review data for sentiment analysis.

Applied TextBlob to classify sentiments as positive or negative.

Performed data analysis to uncover trends, insights, and recommendations for product improvement.

Technologies Used Python 3.x

Selenium: Web scraping and automation

BeautifulSoup: Parsing HTML to extract review data

Pandas: Data cleaning, preprocessing, and analysis

TextBlob: Sentiment analysis

Matplotlib/Seaborn: Data visualization

WordCloud: Generating word clouds from review data

Project Setup Clone the repository:

bash Copy Edit git clone https://github.com/yourusername/iphone-15-sentiment-analysis.git cd iphone-15-sentiment-analysis Install the required Python libraries:

bash Copy Edit pip install -r requirements.txt Data Collection Scraped 300+ customer reviews from the Flipkart page for the iPhone 15 128GB model.

Collected the following data for each review:

Username: Name of the reviewer

Rating: Numerical rating (1–5 stars)

Review Text: The content of the review

Handled pagination to scrape reviews from multiple pages.

Data Preprocessing The following preprocessing steps were applied to the scraped data:

Removed duplicates: Ensured data quality by eliminating duplicate reviews.

Handled missing values: Addressed incomplete or missing review text or ratings.

Text Cleaning:

Converted review text to lowercase.

Removed irrelevant characters, special characters, punctuation, and extra spaces.

Tokenized the text into individual words.

Removed stop words and applied lemmatization to convert words into their base form.

Sentiment Analysis TextBlob was used to analyze the sentiment of each review.

Reviews were classified into:

Positive Sentiment: Polarity score ≥ 0.1

Negative Sentiment: Polarity score < 0.1

The sentiment classification was added to the dataset.

Data Analysis & Insights Sentiment Distribution Analyzed the proportion of positive vs negative reviews.

Average Rating vs Sentiment Investigated the correlation between numerical ratings (1–5 stars) and sentiment polarity to see if higher ratings aligned with more positive sentiments.

Word Cloud Generated a word cloud to highlight the most frequently mentioned terms in both positive and negative reviews.

Review Length Analysis Analyzed whether longer reviews tend to express more detailed sentiments (positive or negative).

How to Run Clone the repository and navigate to the project folder:

bash Copy Edit git clone https://github.com/yourusername/iphone-15-sentiment-analysis.git cd iphone-15-sentiment-analysis Install the necessary dependencies:

bash Copy Edit pip install -r requirements.txt Run the script to scrape reviews and perform sentiment analysis:

bash Copy Edit python sentiment_analysis.py The results, visualizations, and insights will be saved in a generated report.

Results & Insights Key Findings: Sentiment Distribution: A significant portion of the reviews were positive, with most users praising the phone's performance and camera quality.

Common Issues: Negative reviews highlighted concerns over battery life and price.

Positive Highlights: Customers appreciated the design, display quality, and camera improvements.

Review Length: Longer reviews often provided more nuanced feedback, especially negative reviews detailing product drawbacks.

Recommendations: Focus on improving battery life and price value in future iterations.

Highlight camera quality and design in marketing materials based on positive sentiment.

Contributions Contributions are welcome! Please feel free to fork this repository and submit a pull request. If you find any issues or have suggestions for improvement, feel free to open an issue.
