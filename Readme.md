
## Why we built this

As IPFS files grow in number, a search engine will be needed. Google and other mainstream search engines do not crawl IPFS files. The currently existing IPFS search engine at https://ipfs-search.com does not have rank by popularity, is not decentralized enough and is not effecient. So we made this project. 

One can try the search engine at https://ipfs.sarchy.online or at https://gateway.pinata.cloud/ipfs/QmPse2Zoo3njo3P2tMY5RLWvVhczZruG6zMi4Q8YEkZ3FE

If you can access crypto domains, check it at http://sarchy.crypto

## Unique Feature of the search engine.

In this search engine, one can sort webpages by user-defined ranking factors.
For example, the user can increase the ranking for webpages with images.
One can even select unstoppable domains which have gundb chat enabled. 

This way, every user can set their own ranking algorithm instead of Google deciding the ranking algorithm for the whole world. This will stop data manipulation by monopolies and promote decentralization.

## 4 parts of a search engine.

 1. Crawling - Get domain names from unstoppabledomains Ethereum and Zil blockchain. For crawling IPFS pages, Yacy 2 is used. Scrappy python package, apache nutch and commoncrawl db were considered.

 2. Assessing popularity of domain. - Standard page rank like techniques using backlinks and social media popularity can also be used for Ranking. 
Presence of ipfs hash is used as minimum ranking parameter. 
As of now, number of words, number of images, volume of ethereum transactions and outlinks are used as ranking parameters.

 3. Search - Parse content from webpage and put into Elasticsearch

 4. Frontend - UI for search engine. 

## To do

1. Remove bugs while searching
2. Will slowly increase decentralization by moving the data to blockchain and using smart contracts.
3. Ability to upvote pages using metamask auth


## Other Notes

Commands for database creation are in techDocs folder
