# Social-Media-Mining-using-BigData-Platforms
## Big Data Platforms Final Project (The University of Chicago, Physical Sciences Division)

- The main objective of the project is to identify the profiles of Twitterers by analyzng 2TB+ of live tweets, who are tweeting about University of Chicago and compare them to the profiles of Twitterers who are tweeting about other universities. 
- With the results from exploratory data analysis, actionable business recommendations has to be made to help University improve the social media outreach programs. 

## Tools Used: GCP, Hadoop, Dataproc, PySpark SQL, Hive, Twitter API, Python, Matplotlib, Seaborn

## Final Project Instructions

- Identify tweets related to UChicago and 3-4 universities of your choice
  - Choose universities with sufficient tweeter activity
- Discard irrelevant tweets
  - Will be 95%+ of the data
- Complete thorough EDA to identify which variables you can use to profile the Twitterers
  - A lot of variables are poorly populated and will have to be discarded
- Identify the most prolific / influential Twitterers
  - By message volume
  - By message retweet
  - How much are they tweeting about the Universities vs. other topics?
- Where are these Twitterers located?
  - For UChicago
  - For other universities
  - Do you see any relationship between university locations and Twitterers’ locations?
  - Visualize the relationships
- What distinguishes University of Chicago Twitterers vs Twitterers who tweet about other universities
  - Visualize the trends
- What are the timelines of these tweets? Do you see significant peaks and valleys?
  - Do you see data collection gaps?
- How unique are the messages for each of these universities?
  - Are they mostly unique? Or mostly people are just copy-pasting the same text?
  - You can use something like Jaccard similarity / Cosine Similarity / Simhash / Minhash to measure uniqueness / similarity
  - Visualize message duplication (for each university – not between the universities)
  - Please note: this is not a topic modeling (LDA / LSA) – but text similarity analysis.
