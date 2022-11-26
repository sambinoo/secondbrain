# building my secondbrain
**Goal**: I want to create a second brain to log personal bits of knowledge that I can reference back to as I develop my career. This README file is a work in progress and my hope is to update this frequently as I fumble through creating this tool. My secondary goals are to gain practical exposure to Python, SQL, APIs, databases, and Github. 

The project will be broken up into three components:
- Twitter, the data input source
- A database, a location to store data inputs
- A dashboard, the data exported to a UI for a tailored view

## Phase 1:
- explore Twitter API / developer resources to scrape / export personal tweets
  - [Filtered stream](https://developer.twitter.com/en/docs/twitter-api/tweets/filtered-stream/introduction)
  - [Stream tweets real-time](https://developer.twitter.com/en/docs/tutorials/stream-tweets-in-real-time)
  - [Tweepy](https://docs.tweepy.org/en/latest/install.html)
- create a local or public database to store raw data
  - would like to explore non-local options 
- leverage Twitter via [@samsecondbrain](https://twitter.com/samsecondbrain) to create new entries for second brain database
  - may use my personal Twitter [@sambino](https://twitter.com/sambino) to mix my content and keep access convenient
- misc resources: 
  - [Relational Database from Twitter Scraping](https://shihaojran.com/building-a-relational-database-from-twitter-scraping/)

## Phase 2: 
- format / filter tweet metadata / content upon export
  - [Tweet object](https://developer.twitter.com/en/docs/twitter-api/data-dictionary/object-model/tweet)
  - implement my own metadata through the tweet content, ex. `Category: Finance`, `Subject: Crypto`, `Topic: Art`
- populate table(s) with expected metadata

## Phase 3: 
- create a web page / dashboard 
- export table content to dashboard


