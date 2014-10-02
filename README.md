# ElasticSearch Dockerfile

[ElasticSearch](http://www.elasticsearch.org/) v0.90.13 for [Docker](https://www.docker.com/).


### Why this Docker?

Both [Kibana](http://www.elasticsearch.org/overview/kibana/) and [Graylog2](http://graylog2.org/) are great tools for real time data analytics.
We wanted to test each product with **a unique** ElasticSearch instance:

* All logs are sent to Graylog2 server
* Graylog2 server sends logs into ElasticSearch
* Both Kibana and Graylog2 web fetch same data from ElasticSearch

⇒ See [Himedia/docker-graylog2](https://github.com/Hi-Media/docker-graylog2) for a full explanation.

![Big picture](https://raw.githubusercontent.com/Hi-Media/docker-graylog2/master/img/big_picture.png)
