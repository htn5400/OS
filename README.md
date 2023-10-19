# RSS News Feed Aggregation 
**Systems application for Concurrently Processing News Feeds**

RSS news feeds are XML documents housing information about online news articles. Many major media corporations serve up RSS feeds summarizing the news stories that have aired and gone to press in the preceding 24 hours.

In this project, we will build a news search engine that has an index of information similar to that held by news.google.com. To do so, we will develop our system to download RSS news feeds and filter the news articles using multithreading and networking with mutexes, conditional variables, semaphores, and queues. 

**Objective** : Maximize parallelism on Stanford's myth machines and concurrently schedule all downloads of news feeds and processing of articles & searches

This project showcases experience with networking and various concurrency patterns that come up in networked applications. The latest version introduces two ThreadPools which dramatically speed up the aggregation of the news feeds. 
