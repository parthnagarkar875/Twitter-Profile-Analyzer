Run the main.ipynb file. 

The purpose of this notebook is to extract various types of information of a specific Twitter profile
and analyze that information for identifying the interests, hobbies, preferences of that specific user. 

The only additional dependency is to install and setup the Stanford NER tagger. 

This analysis extracts the following insights from a user's profile:

1) Name and Location of a user.

2) A graph displaying the sentiments of tweets posted by the user in the specified time. Which include:  
   
   Polarity 0 = Neutral Sentiment
   
   Polarity 1 = Positive Sentiment    
   
   Polarity -1 = Negative Sentiment
   
3) Detection of  nouns mentioned in the tweets posted by the user in the specified time.

4) Detection of named entities which consist of 
   Organization, Person and Location mentioned in the tweets posted by the user.
   
5) A graph displaying the sentiments of tweets liked by the user in the specified time. Which include:  
   
   Polarity 0 = Neutral Sentiment
   
   Polarity 1 = Positive Sentiment    
   
   Polarity -1 = Negative Sentiment
   
 6) Detection of nouns mentioned in the tweets liked by the user since the user created their account. 
 
 7) Detection of named entities which consist
    of Organization, Person and Location mentioned in the tweets liked by the user since the user created their account.
    
 8) Printing top 15 usernames of the users whose tweets were liked most frequently.
 
 9) Printing locations of the top 15 users whose tweets were liked most frequently by the user.
  
 This is just a standalone unit of a bigger project that is currently being designed by me. 
  
  
  
  
  
  
  
  
