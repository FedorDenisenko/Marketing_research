# ad-hoc_analysis
It is answers for 6 questions in Forex club company for marketing team.

Here there is a task. And then there are results.

TASK
############################################################################################

Let's imagine mobile application that receives traffic from different sources. This traffic is not homogeneous and we need to know it better in order to optimize marketing activity

Your task is to analyze dataset in order to find useful insights: what segments of data bring traffic with the best quality (Main metric is conversion rate from lead to client. There can be other metrics as well) 


You can do this by answering following questions:
-How users are distributed over countries?
-How many outliers are there in data (in terms of deposits)?
-Find segments with best conversion rate (client/lead ratio) and explain why you consider them best ones
-Visualize deposits distribution over sources and channels
-What are your advices to marketing team in order to optimize their activity?

To do this you have a synthetic dataset that contains history of users' activities (registrations and deposits)
Data description: client_id - unique id of lead/client. it's assigned during registration and isn't changed anymore 
Country - country of lead/client (iso2). It's in the separate file (countries.csv)
Source - source of traffic acquisition. There are two possible sources (posts and telegram channel). if Source contains "postid" - it means that lead came from article. id of post doesn't matter. if Source contains "telegram" - it means that lead came from telegram  
channel - channel of traffic. For example, user can come from 'telegram' source and from 'affiliate' channel
Clicks - amount of clicks user made during first day after registration
Latency - time of application loading in miliseconds
Depo - amount of deposit, USD


Expected result is Jupyter notebook with Python code showing answers to questions above

Glossary:
Lead: user who registered inside mobile app
Client: user who registered inside mobile app AND made a deposit


RESALTS 
############################################################################################
Here there are advises for marketing team after ad-hoc analysis.

1). Develop advertisements in facebook to create attractive way to telegram for users. For example facebook gives the biggest amount of users for posts and the best conversion rate for posts. That is why it is very important to develop marketing in facebook with links to telegram also. It can give more users then it is now.
  
2). There are zero users, who has come from social media in post source. It looks strangely because social media in telegram has given 325849 profit. So this problem must be checked. Perhaps it is a technical wrong or users can not buy in this way.
  
3). The best segment of users is smm too telegram. It has the best conversion rate. Focus marketing activities on finding the same customers
 
4). Affiliate channel has low efficiency for posts. Such as amount of users from facebook to posts is 7.06 times as large as from affiliate to post. But total deposit from facebook to post is 12.58 times as large as from affiliate. So it is important to develop markeiting in affiliate to post and telegram. 
  
5). Direct lag behind the facebook source in terms of conversion rate and amount of deposit distribution. From direct users successfully go to telegram, but to post it is worse. That is why it needs to do this channel more attractive for post users.
  
