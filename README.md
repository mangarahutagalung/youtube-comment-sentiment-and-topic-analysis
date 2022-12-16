# youtube-comment-sentiment-and-topic-analysis
TLDR: A sentiment analysis + topic modeling from YouTube comments, including the tool to scrape the comments.

This is a class project that I did at Penn. The goal here is to easily extract comments from YouTube and then analyze the sentiment level of said video and potential topics created from the comment section. The sentiment analysis is pretty straightforward. It classes a comment into 2-5 classes, depending on the model that you are using. The topic analysis is done using BERTopic. The main objective of this analysis is to find out:
1. What do viewers like/dislike about the video
2. What do the viewers like to see for the next video

In the notebook example listed in this repo, we analyzed several YouTube videos discussing about top movies of all time. The goal here is to find out whether:
1. How many viewers agree/disagree with the list
2. See if viewers have their own list/recommendation

The next iteration of this project is to use YouTube comments data as a feature to create our own movie recommendation engine. 
