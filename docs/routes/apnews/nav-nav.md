# AP News - Topics

## Coverage
`index-only`

## Route
- Namespace: `apnews`
- Namespace Name: `AP News`
- Route Path: `/nav/:nav{.*}?`
- Route Name: `Topics`
- Example: `/apnews/topics/apf-topnews`
- URL: `apnews.com`
- Language: `en`
- Categories: `traditional-media`
- Maintainers: `zoenglinghou, mjysci, TonyRL`
- Source Location: `topics.ts`
- Source Module: `() => import('@/routes/apnews/topics.ts')`

## Description
_None_

## Parameters
- `topic`: {"default": "trending-news", "description": "Topic name, can be found in URL. For example: the topic name of AP Top News [https://apnews.com/apf-topnews](https://apnews.com/apf-topnews) is `apf-topnews`"}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `apnews.com/hub/:topic`
- `target`: `/topics/:topic`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/apnews/topics/apf-topnews",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "topics.ts",
  "maintainers": [
    "zoenglinghou",
    "mjysci",
    "TonyRL"
  ],
  "module": "() => import('@/routes/apnews/topics.ts')",
  "name": "Topics",
  "parameters": {
    "topic": {
      "default": "trending-news",
      "description": "Topic name, can be found in URL. For example: the topic name of AP Top News [https://apnews.com/apf-topnews](https://apnews.com/apf-topnews) is `apf-topnews`"
    }
  },
  "path": [
    "/topics/:topic?",
    "/nav/:nav{.*}?"
  ],
  "radar": [
    {
      "source": [
        "apnews.com/hub/:topic"
      ],
      "target": "/topics/:topic"
    }
  ],
  "view": 0
}
```
