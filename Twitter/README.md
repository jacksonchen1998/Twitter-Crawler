# Twitter-Crawler

Crawling Twitter's reply and save their contents and likes

## Dataset

### [Famous Words Twitter Dataset](https://www.kaggle.com/datasets/jackksoncsie/twitter-dataset-keywords-likes-and-tweets)

|Name|type|Description|
|:---:|:---:|:---:|
|keyword|`str`|Keyword of the tweet|
|likes|`int`|Number of likes|
|tweet|`str`|Content of the tweet|

## Usage

Top 20 keywords in 2021, each keyword has `5000` tweets
```
"COVID-19",
"Vaccine",
"Zoom",
"Bitcoin",
"Dogecoin",
"NFT",
"Elon Musk",
"Tesla",
"Amazon",
"iPhone 12",
"Remote work",
"TikTok",
"Instagram",
"Facebook",
"YouTube",
"Netflix",
"GameStop",
"Super Bowl",
"Olympics",
"Black Lives Matter"
"India vs England",
"Ukraine",
"Queen Elizabeth",
"World Cup",
"Jeffrey Dahmer",
"Johnny Depp",
"Will Smith",
"Weather",
"xvideo",
"porn",
"nba",
"Macdonald",
```

![](../image/tweet.png)

### [Famous Words Twitter Reply Dataset](https://www.kaggle.com/datasets/jackksoncsie/famous-keyword-twitter-replies-dataset?rvi=1)

|Name|type|Description|
|:---:|:---:|:---:|
|keyword|`str`|Keyword of the tweet|
|main_tweet|`str`|Content of the tweet|
|main_likes|`int`|Number of likes of the tweet|
|reply|`str`|Content of the reply|
|reply_likes|`int`|Number of likes of the reply|

```
search_terms = [
    "COVID-19",
    "Vaccine",
    "Zoom",
    "Bitcoin",
    "Dogecoin",
    "NFT",
    "Elon Musk",
    "Tesla",
    "Amazon",
    "iPhone 12",
    "Remote work",
    "TikTok",
    "Instagram",
    "Facebook",
    "YouTube",
    "Netflix",
    "GameStop",
    "Super Bowl",
    "Olympics",
    "Black Lives Matter"
    "Ukraine",
    "Queen Elizabeth",
    "World Cup",
    "weather",
    "nba",
    "Macdonald",
    "K-pop",
    "music",
    "movie",
    "sport",
    "news",
    "science",
]
```

![](../image/reply.png)

## Other program

- `count.py` : Count the number of tweets and replies
- `check.py` : Check json file format
- `search.py` : Count the number of likes of each reply

## Method

Using [Snscrape](https://github.com/JustAnotherArchivist/snscrape)

Install Snscrape

`pip3 install snscrape`

Development version

`pip3 install git+https://github.com/JustAnotherArchivist/snscrape.git`

## Reference

- [Web Scraping with Python – How to Scrape Data from Twitter using Tweepy and Snscrape](https://www.freecodecamp.org/news/python-web-scraping-tutorial/)
- [Tweepy](https://github.com/tweepy/tweepy)
- [Snscrape](https://github.com/JustAnotherArchivist/snscrape)
- [Twitter Developer](https://developer.twitter.com/en)
