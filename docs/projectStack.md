# Technologies Needed For App

## Frontend :- 
Needs to be simple and welcomming to use.

-- [Technology] React Native. Very familiar, and I would like to create a project myself. 
	This will also extend well for mobile. 
-- Journal Logic: Track journal entries along with relevant information like date & sentiment
-- Sentiment of each journal: Will need some display summing up the general sentiment observed by a journal entry
-- General sentiment: Show data related to gathered sentiment history. This should
	be something like overall hapiness level over past week. 
-- Explanation of different sentiments and what they might indicate. This should mainly
	aim to catch depression, but could be extended to track other things like anxiety & 
	other mental thigns.
-- Use warm welcomming/soothing colors as people comming to this app will likely be in a
	depressed state. Something as simple as color should be taken into account.
-- React Native is perfect because it allows native integration for this tool across web, ios and android.  


## Backend :- 
Initially just considered making data storage calls directly through front end. That
being said, this might have an effect on how the general website function and bring up
security risks. Not good when dealing with peoples very heartfelt, honest and naked data. 

-- [Technology] NodeJS. Pretty much the standard for web servers. The backend shouldn't be 
	that complex so no need to overthink this. 
-- Look into security for things like db keys and db storage. 
-- Extending on previous point, make sure message data gets encrypted before its stored. 
-- Will need to use a sentiment analysis DB. Considering how far some of these speech
	bots have gotten, there might be very solid out of the box sollutions. Otherwise
	need to train own model


## Storage :- 
Considered local storage, but this was not a good idea because of security/scalability.
That being said I would like to try saving data to a local sql storage if it can be easily 
translate. Azure has features to migrate local db data to. 

-- [Technology] SQL Local DB & Cloud DB.  
 
## Modularity & External Journal Support :- 
The novel feature here is the sentiment capturing of journal. That being said, usability
would be significantly improved if data could be imported from other journals. One option
could be google keeps, or penzu if data is publically available

-- Find journals with public apis
