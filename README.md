# Is-Twitter-a-Good-Source-of-Covid-19-Related-Information

Project objective: identify whether Twitter can be considered a credible source of information, which reflects the risk of contracting a COVID infection.

The project answers the following questions:
Does Twitter activity reflect the trends in rising/decreasing Covid-19 cases around the world? 
Who tweets the most about Covid19? Are they mostly government / health organizations or random users tweeting about their symptoms, vaccination 
status or their attitudes toward the vaccination?
Are most messages original content or simply copies of other tweets? 

Methodology: 
1. Filter tweets to only include those containing Covid-related words. 
2. Assign Twitterers into organizations and categories based on their user desctiption and follower count. The organizations and categories are News, Healthcare, 
Governmental, Celebrity, Influencer, and Other. 
3. Perform location and time analyses to identify Tweet volume patterns.
4. Perform similarity analysis to determine whho posts mostly original content and who simply retweets information. 

Data: 
A nested .json file containing more than 25,000,000 real world tweets were imported from the course instructor's GCP bucket. Thus, it could not be shared. 

The project was completed in PySpark. 

