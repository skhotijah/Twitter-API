# Twitter-API

## How to use?

In order to use this script you should register a data-mining application
with Twitter.  The first step is the registration of your app. In particular, you need to point your browser to http://apps.twitter.com, log in to Twitter (if you’re not already logged in), and register a new application. You can now choose a name and a description for your app (for example “Mining Demo” or similar). You will receive a consumer key and a consumer secret: these are application settings that should always be kept private.

After doing this you can copy and paste your unique consumer key,
consumer secret, access token, and access secret into the load_api()
function below.

```
 consumer_key = 'your unique consumer key'
 consumer_secret = 'your unique consumer_secret'
 access_token = 'your unique access_token'
 access_secret = 'your unique access_secret'
```


The main() function can be run by executing the command: 
python twitter_search.py

I used Python 3 and tweepy version 3.5.0.  You will also need the other
packages imported :

- import tweepy
- from tweepy import OAuthHandler
- import json
- import datetime as dt
- import time
- import os
- import sys
