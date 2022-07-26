<h1>Sentiment Analysis: Reddit Headlines and Comments</h1>

<p>The analyzer uses the pre-trained VADER models in Python's natural language toolkit(NLTK) to perform sentiment analysis on headlines and comments of Reddit posts.
The VADER toolkit has capabilities to understand the intent especially with the content in microblogs such as Reddit. Hence its selection in the project.

Testing includes analysis carried out across 5 subreddits, with 1,000 posts/headlines for each subreddit and 100 comments for each post, for a total of 500,000 comments and 5,000 headlines. The initial idealogy that posts with positive headlines generally should have a larger proportion of positive comments, while posts with negative headlines should have a larger proportion of negative comments has been confirmed with the test results. </p>

<h4>Running Code</h4>
<ul>
  <li>Set reddit client id, secret, and user agent in "combined.py" to run code. A reddit account is required. </li>
  <li>Optionally set a post limit and your desired subreddits in the variables "postLimit" and "subreddits." We recommend setting the post limit to <10 for testing. /li>
  <li>Output is in the format subreddit_headlines_labels.csv and subreddit_comment_labels.csv. For each subreddit, the headlines csv files contain unique post IDs for the posts being analyzed, as well as a negative/neutral/positive label (-1, 0, 1). Similarly, the comments csv file contains the unique post IDs for the posts being analyzed and the distribution and number of comments matching each sentiment label (-1, 0, 1) for each post ID. </li>
</ul>

<h4>Collaborators</h4>
<ul>
  <li> Rahul Arora @rahula00</li>
  <li> Alec Siegel @15siegela </li>
</ul>

    
