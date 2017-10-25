# Cloud Computing Assignment1 TwittMap

	Member: Mingjie Zhao(mz2646) Ming Zhu(mz2655)

## Link:
TwittMap: (http://twittmap-env2.puvggpuugy.us-west-2.elasticbeanstalk.com/)

## Technology:
* Twitter Streaming API, Tweepy 3.5.0
* Google Map API
* Elastic Search 5.5
* Elastic Beanstalk
* Django 1.1.6
* Python 3.6
* jQuery 3.2.1

## Demo:

* Show the most recent 1000 tweets stored in Elasticsearch:
![mostrecent](https://github.com/streammy2013/Cloud-Computing-Assignment1-TwittMap/blob/master/demo%20img/initial.png)

* Search from the dropdown:
	* Search "cat": 
![catsearch1](https://github.com/streammy2013/Cloud-Computing-Assignment1-TwittMap/blob/master/demo%20img/search-cat.png)
![catsearch2](https://github.com/streammy2013/Cloud-Computing-Assignment1-TwittMap/blob/master/demo%20img/search-cat-2.png)
	* Search "photography":
![photo1](https://github.com/streammy2013/Cloud-Computing-Assignment1-TwittMap/blob/master/demo%20img/search-photography.png)
![photo2](https://github.com/streammy2013/Cloud-Computing-Assignment1-TwittMap/blob/master/demo%20img/search-photography2.png)
* Search from the input box:
	* Search "apple":
![apple1](https://github.com/streammy2013/Cloud-Computing-Assignment1-TwittMap/blob/master/demo%20img/search-apple.png)
* Search from a random point clicked by user:
 	* Search nearest 1000km tweets:
![geo](https://github.com/streammy2013/Cloud-Computing-Assignment1-TwittMap/blob/master/demo%20img/geosearch.png)

Note: There are about 30,000+ tweets in ElasticSearch. Also, because tweets are added continuously, there may be some difference between those demo pictures.


