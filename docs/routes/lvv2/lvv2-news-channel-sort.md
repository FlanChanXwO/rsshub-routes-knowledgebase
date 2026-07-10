# LVV2 - 频道

## Coverage
`index-only`

## Route
- Namespace: `lvv2`
- Namespace Name: `LVV2`
- Route Path: `/lvv2/news/:channel/:sort?`
- Route Name: `频道`
- Example: `/lvv2/news/sort-score`
- URL: `lvv2.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `Fatpandac`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
|   热门   |   最新   |    得分    |   24 小时榜   |
| :------: | :------: | :--------: | :-----------: |
| sort-hot | sort-new | sort-score | sort-realtime |

| 排序方式 | 一小时内 | 一天内 | 一个周内 | 一个月内 |
| :------: | :------: | :----: | :------: | :------: |
|          |  t-hour  |  t-day |  t-week  |  t-month |

## Parameters
- `channel`: 频道，见下表
- `sort`: 排序方式，仅得分和24小时榜可选填该参数，见下表


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "|   热门   |   最新   |    得分    |   24 小时榜   |\n| :------: | :------: | :--------: | :-----------: |\n| sort-hot | sort-new | sort-score | sort-realtime |\n\n| 排序方式 | 一小时内 | 一天内 | 一个周内 | 一个月内 |\n| :------: | :------: | :----: | :------: | :------: |\n|          |  t-hour  |  t-day |  t-week  |  t-month |",
  "example": "/lvv2/news/sort-score",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "频道",
  "parameters": {
    "channel": "频道，见下表",
    "sort": "排序方式，仅得分和24小时榜可选填该参数，见下表"
  },
  "path": "/news/:channel/:sort?",
  "topFeeds": []
}
```
