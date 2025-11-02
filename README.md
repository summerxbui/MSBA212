# MSBA212
Assignment Overview: This assignment focuses on finding posts that is related to weddings and wedding planning checklist. The code for this will fetch related posts from Reddit through Reddit API. 
How to run: 
1. Prerequisites: Python version 3.12.4
2. Installation: install package Praw by typing the following code in command promp/terminal
   pip install praw
3. Configuration: open reddit.env and fill in your credentials from your credit API. Please save the env file in the same folder as your .inyb or .py file
4. Execution: When open the code file, please change the subreddits to the name of the 3 subreddits you are most interested in. Also, change the limit of posts and the file name to your preference. Then, run the code. For the 2nd task code, change the search query to the keyword that you want to search, the subreddits and the name of the file to fit your topic of interest.
Output: The output of the files should contain the following columns:
  title: The full title of the post (String)
  score: The net score of upvotes - downvotes(Integer)
  upvote_ratio: Ratio of upvotes to total votes. A proxy for quality. (Float)
  num_comments: The total number of comments on the post (Integer)
  author: The username of the post’s author (String)
  subreddi t:The subreddit where the post originated (String)
  url:The external URL the post links to (if not a text post)(String)
  permalink: The permanent URL to the Reddit post itself (String)
  created_utc: The Unix timestamp of post creation (Integer or String)
  is_self: True if it is a text-only post, False otherwise. (Boolean)
  selftext: The body text of the post (truncate to 500 chars). (String)
  flair: The category flair/tag assigned to the post. (String)
  domain: The domain of the linked content (e.g., "github.com"). (String)
  search_query: The search term used to find this post (if any). (String)
flair The category flair/tag assigned to the post. String
domain The domain of the linked content (e.g., "github.com"). String
search_query The search term used to find this post (if any). String
