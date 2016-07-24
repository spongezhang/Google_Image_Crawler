### Introduction

This code proposes to crawl image from google custom search. Restricted by Google, each keywords can only get 100 results and each 10 results cost 1 query
 in your google custom search account(100 queries per day for free). 

### Setting your own Google custom search

0. **Google Developers Account** 
  0. Creat your own account on https://developers.google.com/.
0. **Setup your own API**
  0. Go to https://console.developers.google.com/, setup your own custom search API
  0. Create your own credentials for server and remember the key.(API key)
0. **Setup for your own search engine**
  0. Go to https://cse.google.com/cse/all to add a new engine.
  0. Go to setting part, change the engine to search for the whole internet and delete the site set in the previous step
  0. Also find your search engine id.(Engine id)

### Running the code

1. Open custom_search.py file. Set the your_develop_key as API key and your_engine_cx as your Engine id

2. Change the query and the setting as you want and run the code.
