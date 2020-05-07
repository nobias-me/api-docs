---
title: API Reference

toc_footers:
  - <a href='#'>Questions? Email anant.goel@nobias.com </a>

search: true
---

# Introduction

Welcome to the Nobias Finance API! These API endpoints can get information on various stocks and authors.

# Stocks

## Get news for a stock

> This endpoint returns JSON structured like this:

```json
{
    "stock": "AAPL",
    "authors": {
        "ykolgK9XRyAbwg": [
            {
                "nobiasLeaning": "Sell",
                "title": "Shares down after Teck Resources withdraws application for Frontier oilsands project",
                "content": "Shares in Teck Resources Ltd. are trading down four per cent after the company said citing uncertainty over climate policies.\n\nThe Vancouver-based company said it will take a $1.13-billion writedown on the Frontier project in Alberta, which was expected to create thousands of jobs but was also produce about four million tonnes of greenhouse gas emissions per year over 40 years. In a letter to the federal environment minister, Teck CEO and President Don Lindsay says investors and customers increa",
                "url": "https://globalnews.ca/news/6588417/teck-resources-withdraws-frontier-oilsands-project-shares/",
                "accurate": null,
                "date": "2020-02-24T16:18:55Z"
            }
        ],
        "I9QRyk7yuaViJg": [
            {
                "nobiasLeaning": "Buy",
                "title": "Dow Futures Point to Fresh Record Highs As China Cuts US Tariffs, Grapples With Coronavirus",
                "content": "The Thursday Market Minute \n\nGlobal stocks rally, while U.S. equity futures point to fresh record highs on Wall Street, as China moves to both contain the coronavirus spread and cut tariffs on U.S.-made goods to help bolster its economic response. \nChina's tariff reductions, while linked to the December Phase 1 trade agreement, suggest its prepared to meeting commitments on agricultural and energy purchases this year despite the expected coronavirus slump. \nHealth authorities confirm another 3,0",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y4Y-HPD1-F00X-J2P6-00000-00",
                "accurate": true,
                "date": "2020-02-06T09:39:17Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Apple Scraps Q2 Revenue Guidance; Says Coronavirus Will Hit iPhone Supplies, China Demand",
                "content": "Apple Inc.  scrapped its second quarter revenue guidance Monday, citing the ongoing impact of the coronavirus outbreak in China, and noted that iPhone shortages would affect the tech giant's near-term sales.\n\nApple said manufacturing sites in China that had been closed by government officials following the coronavirus outbreak were coming back on line, but added the company was experiencing \"a slower return to normal conditions than we had anticipated.\" Apple said iPhone supplies will be tempora",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y7C-83C1-F00X-J0DH-00000-00",
                "accurate": true,
                "date": "2020-02-17T22:01:16Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Apple Scraps Q2 Revenue Guidance; Says Coronavirus Will Hit iPhone Supplies, China Demand",
                "content": "Apple cautioned investors Monday that the ongoing coronavirus outbreak  would hit global iPhone supplies and near-term revenues. \nApple Inc.  ( AAPL ) - Get Report  scrapped its second quarter revenue guidance Monday, citing the ongoing impact of the coronavirus outbreak in China, and noted that iPhone shortages would affect the tech giant's near-term revenues. \n\nApple said manufacturing sites in China that had been closed by government officials following the coronavirus outbreak were coming bac",
                "url": "https://www.thestreet.com/investing/apple-scraps-q2-revenue-guidance-amid-coronavirus-spread",
                "accurate": true,
                "date": "2020-02-17T21:33:54Z"
            },
            {
                "nobiasLeaning": "Sell",
                "title": "Roku Shares Surge As Disney, Apple Launches Drive Solid Q4 Revenue Gains",
                "content": "Roku Inc.  shares jumped higher in pre-market trading Friday after it posted stronger-than-expected fourth quarter revenues, and topped Street estimates for near-term sales, as customers flocked to its streaming service platform amid the launch of new offering from Disney and Apple. \n\nRoku recorded a narrower-than-expected fourth quarter loss of 13 cents per share over the three months ending in December, as revenues surged nearly 50% to $411.2 million. Roku added 4.6 million new customers over ",
                "url": "http://metabase.moreover.com/noarticleurl?type=psh&lni=5Y6N-CGV1-JCHV-V0VM-00000-00",
                "accurate": true,
                "date": "2020-02-14T10:07:01Z"
            }
        ],
    }
}
```

This endpoint retrieves all news for a given stock.

### HTTP Request

`GET https://api.nobias.com/v1/spotcheck/finance/stock/news/<TICKER>`

### URL Parameters

Parameter | Description
--------- | -----------
TICKER | The ticker of the stock you want news for (example: AAPL for Apple)

### Response fields

#### stock
Ticker of the stock you requested news for

#### author
Json object containing news articles indexed by author. Keys are authorId and values are a list of news objects

##### nobiasLeaning
string value showing Nobias's rating. Possible values "Buy", "Sell", "Unknown"

##### title
Title of the news article

##### content
Content of the news article (only a snippet, not the full article)

##### url
URL of the news article

##### accurate
boolean value indiciating if this article predicts the stock movement correctly. Possible values true, false and null

##### date
Date/time the news article was written (UTC)

## Get metadata for a stock

> This endpoint returns JSON structured like this:

```json
{
    "stock": "AAPL",
    "authors": [
        {
            "id": "random_id",
            "name": "name of the author",
            "accuracy": 0.8,
            "n_articles": 10,
        },
        {
            "id": "random_id2",
            "name": "name of the author2",
            "accuracy": 0.6,
            "n_articles": 5,
        },
    ],
    "n_buy": 10,
    "n_sell": 3,
    "n_neutral": 5,
}
```

This endpoint retrieves metadata for a given stock.

### HTTP Request

`GET https://api.nobias.com/v1/spotcheck/finance/stock/meta/<TICKER>`

### URL Parameters

Parameter | Description
--------- | -----------
TICKER | The ticker of the stock you want metadata for (example: AAPL for Apple)

### Response fields

#### stock
Ticker of the stock you requested news for

#### author
Array containing metadata indexed by author

##### id
Author Id

##### name
Author Name

##### accuracy
float value showing % of articles this author wrote on this stock that were correct

##### n_articles
number of articles written by this author on this stock

##### n_buy
number of articles written on this stock with nobiasLeaning of "Buy"

##### n_sell
number of articles written on this stock with nobiasLeaning of "Sell"

##### n_neutral
number of articles written on this stock with nobiasLeaning of "Neutral"


# Authors

## Get news for an author

> This endpoint returns JSON structured like this:

```json
{
    "authorId": "oS_N5x9jbYqfcg",
    "name": "Gary Stephens",
    "stocks": {
        "TSLA": [
            {
                "nobiasLeaning": "Buy",
                "title": "Robert W. Baird Raises Tesla (NASDAQ:TSLA) Price Target to $650.00",
                "content": "Tesla (NASDAQ:TSLA) had its target price upped by analysts at Robert W. Baird  from $525.00 to $650.00 in a research report issued on Thursday, BenzingaRatingsTable reports. The firm presently has a “neutral” rating on the electric vehicle producer’s stock. Robert W. Baird’s price target would indicate a potential downside of 0.09% from the stock’s previous close. \n \nOther equities analysts have also issued reports about the stock. BidaskClub upgraded shares of Tesla from a “buy” rating to a “st",
                "url": "https://www.modernreaders.com/news/2020/02/01/robert-w-baird-raises-tesla-nasdaqtsla-price-target-to-650-00.html",
                "accurate": null,
                "date": "2020-02-01T09:36:35Z"
            }
        ],
        "AAPL": [
            {
                "nobiasLeaning": "Sell",
                "title": "Apple Inc. Forecasted to Earn Q2 2020 Earnings of $3.00 Per Share (NASDAQ:AAPL)",
                "content": "Apple Inc. (NASDAQ:AAPL) – Research analysts at  Jefferies Financial Group decreased their Q2 2020 earnings per share estimates for Apple  in a research report issued on  Wednesday, January 29th. Jefferies Financial Group analyst K. Mcnealy now expects that the iPhone maker will post earnings of $3.00 per share for the quarter, down from their previous estimate of $3.05. Jefferies Financial Group currently  has a “Buy” rating and a $350.00 target price on the stock. Jefferies Financial Group als",
                "url": "https://www.modernreaders.com/news/2020/02/02/apple-inc-forecasted-to-earn-q2-2020-earnings-of-3-00-per-share-nasdaqaapl.html",
                "accurate": true,
                "date": "2020-02-02T08:19:06Z"
            }
        ],
        "FB": [
            {
                "nobiasLeaning": "Buy",
                "title": "Jefferies Financial Group Research Analysts Increase Earnings Estimates for Facebook, Inc. (NASDAQ:FB)",
                "content": "Facebook, Inc. (NASDAQ:FB) – Analysts at  Jefferies Financial Group lifted their FY2020 earnings per share estimates for shares of Facebook  in a research note issued to investors on  Monday, January 27th. Jefferies Financial Group analyst B. Thill now anticipates that the social networking company will earn $9.72 per share for the year, up from their prior estimate of $7.92. Jefferies Financial Group currently  has a “Buy” rating and a $250.00 target price on the stock. \n \nFacebook (NASDAQ:FB) ",
                "url": "https://www.modernreaders.com/news/2020/02/01/jefferies-financial-group-research-analysts-increase-earnings-estimates-for-facebook-inc-nasdaqfb.html",
                "accurate": true,
                "date": "2020-02-01T10:23:58Z"
            }
        ]
    }
}
```

This endpoint retrieves all news articles for a given author.

### HTTP Request

`GET https://api.nobias.com/v1/spotcheck/finance/author/news/<ID>`

### URL Parameters

Parameter | Description
--------- | -----------
ID | The id of the author you want news for 

### Response fields

These fields are roughly the same as the Stock APIs, let me know if you have questions.

## Get metadata for an author

> This endpoint returns JSON structured like this:

```json
{
    "authorId": "some_id",
    "name": "Some Author",
    "imageUrl": "http://url.com/someimage.png",
    "accuracy": [0.1, 0.8, 0.1, 0.5],
    "rank": 5,
    "stars": 3.5,
    "n_totalAuthors": 1579,
    "stocks": {
        "TSLA": {
            "accuracy": 0.8,
            "n_buy": 10,
            "n_sell": 3,
            "n_neutral": 5,
        },
        "AAPL": {
            "accuracy": 0.3,
            "n_buy": 10,
            "n_sell": 3,
            "n_neutral": 5,
        }
    },
}
```

This endpoint retrieves metadata for a given author.

### HTTP Request

`GET https://api.nobias.com/v1/spotcheck/author/meta/<ID>`

### URL Parameters

Parameter | Description
--------- | -----------
ID | The id of the author you want metadata for

### Response fields

Field definitions are the same as Stock API, the only new fields are 

#### author.accuracy
This is an array of float values, arr[0] represents the accuracy for the last quarter, and it subsequent value represents accuracy for the quarter after. So if arr[0] is FY20Q2 then arr[1] is FY20Q1 and arr[2] is FY19Q4 and so on...

#### author.stars
The star rating for the author

#### author.rank
The rank for the author
