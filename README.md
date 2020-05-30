<h1 align="center"><a id="user-content--robot-go-karuna-karuna-go-warning-" class="anchor" aria-hidden="true" href="#-robot-go-karuna-karuna-go-warning-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><g-emoji class="g-emoji" alias="india" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f1ee-1f1f3.png">🇮🇳</g-emoji> <g-emoji class="g-emoji" alias="robot" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f916.png">🤖</g-emoji> Twitter Profile Analyzer <g-emoji class="g-emoji" alias="microbe" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f9a0.png">:computer:</g-emoji><g-emoji class="g-emoji" alias="warning" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/26a0.png">⚠️</g-emoji> </h1>

Run the main.ipynb file. 

The purpose of this notebook is to extract various types of information of a specific Twitter profile
and analyze that information for identifying the interests, hobbies, preferences of that specific user. 

For illustrative purpose, I have scanned the profile and extracted insights from the user @GTThampi2.

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
  
  
  
  
  
  
  
  
