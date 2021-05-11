# Twitter_Data_Retrieval
This project is a part of an flutter application that helps people with resources connect to people in need of support. Tweepy library is used to authorize twitter api and retrieve tweets. Then the data is parsed and stored in a pandas dataframe. 

After successfully completing this task the data the contact info and location is extracted from tweets using regex and fuzzywords library. The fuzzywords library compares a sentence with a lost of strings and matches it with the one it matches the most. It helps in extarction of location of the individual who tweeted. 

Moreover, we mount the dataFrame in CSV form in google drive from where it could be utilized in the front end (flutter application) and the goal could be accomplished. 
