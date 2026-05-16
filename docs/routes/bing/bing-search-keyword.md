# Bing - 搜索

## Coverage
`index-only`

## Route
- Namespace: `bing`
- Namespace Name: `Bing`
- Route Path: `/bing/search/:keyword`
- Route Name: `搜索`
- Example: `/bing/search/rss`
- URL: `cn.bing.com/`
- Language: `_None_`
- Categories: `other`
- Maintainers: `CaoMeiYouRen`
- Source Location: `search.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `keyword`: 搜索关键词


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
  - `cn.bing.com/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/bing/search/rss",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "search.ts",
  "maintainers": [
    "CaoMeiYouRen"
  ],
  "name": "搜索",
  "parameters": {
    "keyword": "搜索关键词"
  },
  "path": "/search/:keyword",
  "radar": [
    {
      "source": [
        "cn.bing.com/"
      ],
      "target": ""
    }
  ],
  "topFeeds": [],
  "url": "cn.bing.com/"
}
```
