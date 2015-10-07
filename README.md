# Running Node.js on App Engine

Tweets feed example using Twitter API and node.js for showing Node.JS applications running on Google Cloud Platform.

## Requirements
* [node.js](http://nodejs.org/)

## Installation
```sh
$ git clone https://github.com/leopittelli/nodengine.git
$ npm install
```
* Create a [twitter app](https://dev.twitter.com/apps/new)
* Fill the ```consumer_key```, ```consumer_secret```, ```access_token``` and the ```access_token_secret``` in the ```config.js``` file
* Run ```$ npm start```
* Visit: ```http://localhost:8080```

## Dependencies
Its built based on:
* Twitter API Client for node [twit](https://github.com/ttezel/twit)
* Express web framework for Node.js [express](http://expressjs.com/)
* Mustache template system. [mustache-express](https://github.com/bryanburgers/node-mustache-express)

## Deployment
It's prepared to run on app engine. (I started from the [Google Cloud Platform getting starter](https://github.com/GoogleCloudPlatform/nodejs-getting-started)).
You can follow the [node.js getting started article](https://cloud.google.com/nodejs/getting-started).