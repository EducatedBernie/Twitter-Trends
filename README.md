# Twitter-Trends Project!

A geographic visualization of Twitter data across the USA. The map displayed above depicts how the people in different states feel about Texas. Used dictionaries, lists, and data abstraction techniques to create this modular program. 

Run py trends.py -m texas to create the visualization shown!

![alt text](https://i.imgur.com/CbSKSlb.png)


This image is generated by:

Collecting public Twitter posts (tweets) that have been tagged with geographic locations and filtering for those that contain the "texas" query term,
Assigning a sentiment (positive or negative) to each tweet, based on all of the words it contains,

Aggregating tweets by the state with the closest geographic center, and finally

Coloring each state according to the aggregate sentiment of its tweets. Red means positive sentiment; blue means negative.

You need to put all_tweets.txt into the data folder before you can do this. Get all_tweets.txt from my Google Drive. 
