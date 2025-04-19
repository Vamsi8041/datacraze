🐦 Twitter Data Dashboard 📊

This Streamlit application is an interactive dashboard for visualizing and analyzing Twitter data, including metrics like retweets, likes, views, language distribution, verification status, and author follower statistics.

------------------------------------------------------------
🚀 Features

- Interactive Filters: Filter tweets by language and date range.
- Key Metrics: Displays total tweets, likes, retweets, and average engagement stats.
- Engagement Trends: Line charts showing daily trends in retweets, likes, and views.
- Language Analysis: Pie chart showing distribution of tweets by language.
- Verification Insights: Box plot comparing engagement between verified and non-verified users.
- Engagement Comparison: Scatter plot of retweets vs. likes.
- Followers Distribution: Histogram showing follower count distribution.
- Correlation Matrix: Heatmap showing correlations between engagement metrics.
- Daily Retweet Averages: Bar plot of average retweets per day.

------------------------------------------------------------
🧰 Requirements

- Python 3.7 or higher
- pip package manager

Required Python Libraries:
Install them using this command:

    pip install -r requirements.txt

Sample `requirements.txt` content:

    streamlit
    pandas
    plotly

------------------------------------------------------------
📁 File Structure

.
├── final_preprocessed.csv       <- Your input CSV file
├── app.py                       <- Main Streamlit application script
├── requirements.txt             <- List of dependencies
└── README.txt                   <- This file

------------------------------------------------------------
▶️ How to Run

1. Make sure the dataset file (final_preprocessed.csv) is in the same folder as app.py

2. Open your terminal and run the following command:

    streamlit run app.py

3. This will launch the dashboard in your default web browser at http://localhost:8501

------------------------------------------------------------
📋 Notes on the Dataset

Your CSV file should include the following columns:

- date (datetime)
- retweetCount (numeric)
- likeCount (numeric)
- viewCount (numeric)
- author_followers (numeric)
- author_following (numeric)
- lang (language code like 'en', 'es', etc.)
- author_isVerified (True/False or 1/0)

Make sure these columns exist and are clean to avoid processing errors.

------------------------------------------------------------
🙌 Acknowledgements

This project is built using:

- Streamlit
- Plotly
- Pandas

------------------------------------------------------------
📬 Contact

For questions, feedback, or support, please open an issue or reach out to the developer.
