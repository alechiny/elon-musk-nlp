# Project 3.  Monitoring Elon Mask's persona and businesses

### Introduction
Elon Musk, the founder of Tesla and SpaceX, has asked his PR office to monitor social media to understand how both, his persona and his business are being perceived on social media. 
Mr. Musk is not immune to controversy: his unorthodox leadership style,  spontaneous mass communication, and more recently the sale of an estimated $6.9 billion in Tesla stocks (https://www.wsj.com/articles/elon-musks-possible-tesla-share-sale-comes-as-the-taxman-looms-11636482029) make him a topic of many posts and conversations all over the internet.
Reddit, an American social news aggregation and discussion web site was selected for a preliminary investigation on this topic because of its unique position as an aggregator of news and opinion.  Reddit ranks as the 19th-most-visited website in the world and 7th most-visited website in the U.S. (https://en.wikipedia.org/wiki/Reddit).  


#### Methods
We first searched for ‘Elon Musk’ in the news subreddit to understand which words are associated with his name.  We vectorized a total of 1,998 posts, eliminated the most frequent stop words in the English dictionary and ranked the first 15 in ascending order.  The results showed Elon Mask’s name associated with his business ventures, wealth, his twitter hashtag elon_musk, bit coins,  and two other billionaires, Bill Gates and Jeff Bezos.   
To understand how both Tesla and SpaceX are reported and spoken about we searched both subreddits for a total of 3,998 subreddits, equally divided between the two subreddits.  The text of the subreddits were vectorized and analyzed for content.  Exploratory data analysis was carried out to show the relationship of the most common words in both subreddits.  Three statistical models, logistic regression, random trees and a pipeline combining both  were created to classify words for the two subreddits.   For each model the top words were sorted, confusion matrix and predicted probability were charted for analysis.


### Results
The results of the news search showed that Elon Mask’s name is associated with his business ventures, wealth, his twitter hashtag elon_musk, bit coins, and two other billionaires, Bill Gates and Jeff Bezos.  These preliminary results are part of an exploratory data analysis that is not conclusive.  More posts should be analyzed to have a clearer picture of the sentiment toward Elon Mask.
The best predictor we tested was the logistic regression, followed by the pipeline and decision trees.  
The confusion matrix of the logistic regression showed a precision of 94%, a recall of 88% and a specificity of 95%; the decision trees confusion matrix showed a precision of 70%, a recall of 99% and a specificity of 61%.  The pipeline showed a confusion matrix with a precision of 92%, a recall of 90% and a specificity of 92%. The results of the logistic regression and the pipeline are comparable, while the decision tree showed a high number of type I errors. 


### Conclusions
Elon Mask’s name is associated with his business ventures, wealth, twitter, his twitter hashtag elon_musk, bitcoins, and two other billionaires, Bill Gates and Jeff Bezos.  These preliminary results are part of an exploratory data analysis that is not conclusive.  More posts should be analyzed to have a clearer picture of the sentiment toward Elon Musk.
The best predictor we tested was the logistic regression, followed by the pipeline and decision trees.  
