Reddit Data Scraper & Preprocessing

This project scrapes posts from the subreddit WallStreetBets using the praw library, processes the data into a pandas DataFrame, and performs text preprocessing on the post titles and bodies. The cleaned data can be saved to CSV and Excel files for further analysis.

Features
       •	Scrape the top 1000 posts from the WallStreetBets subreddit.
       •	Clean and preprocess post titles and bodies using nltk.
       •	Save the cleaned data to CSV and Excel files.

Dependencies
  Make sure you have the following dependencies installed:
       •	Python 3.6+
       •	pandas
       •	praw
       •	nltk
       •	re (for regular expressions)
 
 You can install all the dependencies using the following command
       #  pip install pandas praw nltk



Setup Instructions

1. Reddit API Credentials
To use the Reddit API, you'll need to create a Reddit App and get the following credentials:

    • client_id
    • client_secret
    • user_agent


2. NLTK Setup

The script uses the nltk library for tokenization and removing stopwords.


3. Running the Script

The script will
     • Scrape posts from the WallStreetBets subreddit.
     •  Clean and preprocess the titles and bodies of the posts.
     •  Save the cleaned data to both CSV and Excel files.

4. Output Files

The script generates two output files:
    • reddit_posts.csv: Contains the scraped data in CSV format.
    • reddit_posts.xlsx: Contains the same data in Excel format.
