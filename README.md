# Image Scrambler Twitterbot
Python-built twitterbot that takes images tweeted to it and scrambles them.

## Technologies Used
* Python
* Twitter API
* Tweepy
* Pillow

## Installation
Create a secrets.py file within the root folder. Add the following information to the file:

```
consumer_key = 'YOUR-CONSUMER-KEY'
consumer_secret = 'YOUR-CONSUMER-SECRET'
access_token = 'YOUR-ACCESS-TOKEN'
access_secret = 'YOUR-ACCESS-SECRET'
```
Set up your environment in the terminal with:
```
virtualenv ENV
source bin/activate
```
Then install the following:
```
pip install tweepy
pip install Pillow
```
