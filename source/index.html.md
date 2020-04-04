---
title: API Reference

language_tabs: # must be one of https://git.io/vQNgJ
  - shell

toc_footers:
  - <a href='#'>Sign Up for a Developer Key</a>
  - <a href='https://github.com/slatedocs/slate'>Documentation Powered by Slate</a>

includes:
  - errors

search: true
---

# Introduction

Welcome to the Nobias Finance API! These API endpoints can get information on various stocks and authors.

<aside class="notice">
These APIs are a work in progress and have not been deployed it. I will update this page as APIs are deployed, expect them to be available starting 13th April. Please mock these API responses in your code to test. (Which you should continue to do as a good practice even after the API is available)
</aside>

# Stocks

## Get news for a stock

```shell
curl "api.nobias.com/spotcheck/finance/stock/news/<stock_ticker>"
```

> The above command returns JSON structured like this:

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

`GET https://api.nobias.com/spotcheck/finance/stock/news/<TICKER>`

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


# Kittens

## Get All Kittens

```ruby
require 'kittn'

api = Kittn::APIClient.authorize!('meowmeowmeow')
api.kittens.get
```

```python
import kittn

api = kittn.authorize('meowmeowmeow')
api.kittens.get()
```

```shell
curl "http://example.com/api/kittens"
  -H "Authorization: meowmeowmeow"
```

```javascript
const kittn = require('kittn');

let api = kittn.authorize('meowmeowmeow');
let kittens = api.kittens.get();
```

> The above command returns JSON structured like this:

```json
[
  {
    "id": 1,
    "name": "Fluffums",
    "breed": "calico",
    "fluffiness": 6,
    "cuteness": 7
  },
  {
    "id": 2,
    "name": "Max",
    "breed": "unknown",
    "fluffiness": 5,
    "cuteness": 10
  }
]
```

This endpoint retrieves all kittens.

### HTTP Request

`GET http://example.com/api/kittens`

### Query Parameters

Parameter | Default | Description
--------- | ------- | -----------
include_cats | false | If set to true, the result will also include cats.
available | true | If set to false, the result will include kittens that have already been adopted.

<aside class="success">
Remember — a happy kitten is an authenticated kitten!
</aside>

## Get a Specific Kitten

```ruby
require 'kittn'

api = Kittn::APIClient.authorize!('meowmeowmeow')
api.kittens.get(2)
```

```python
import kittn

api = kittn.authorize('meowmeowmeow')
api.kittens.get(2)
```

```shell
curl "http://example.com/api/kittens/2"
  -H "Authorization: meowmeowmeow"
```

```javascript
const kittn = require('kittn');

let api = kittn.authorize('meowmeowmeow');
let max = api.kittens.get(2);
```

> The above command returns JSON structured like this:

```json
{
  "id": 2,
  "name": "Max",
  "breed": "unknown",
  "fluffiness": 5,
  "cuteness": 10
}
```

This endpoint retrieves a specific kitten.

<aside class="warning">Inside HTML code blocks like this one, you can't use Markdown, so use <code>&lt;code&gt;</code> blocks to denote code.</aside>

### HTTP Request

`GET http://example.com/kittens/<ID>`

### URL Parameters

Parameter | Description
--------- | -----------
ID | The ID of the kitten to retrieve

## Delete a Specific Kitten

```ruby
require 'kittn'

api = Kittn::APIClient.authorize!('meowmeowmeow')
api.kittens.delete(2)
```

```python
import kittn

api = kittn.authorize('meowmeowmeow')
api.kittens.delete(2)
```

```shell
curl "http://example.com/api/kittens/2"
  -X DELETE
  -H "Authorization: meowmeowmeow"
```

```javascript
const kittn = require('kittn');

let api = kittn.authorize('meowmeowmeow');
let max = api.kittens.delete(2);
```

> The above command returns JSON structured like this:

```json
{
  "id": 2,
  "deleted" : ":("
}
```

This endpoint deletes a specific kitten.

### HTTP Request

`DELETE http://example.com/kittens/<ID>`

### URL Parameters

Parameter | Description
--------- | -----------
ID | The ID of the kitten to delete

