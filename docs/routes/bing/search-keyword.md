# Bing - 搜索

## Coverage
`index-only`

## Route
- Namespace: `bing`
- Namespace Name: `Bing`
- Route Path: `/search/:keyword`
- Route Name: `搜索`
- Example: `/bing/search/rss`
- URL: `cn.bing.com/`
- Language: `zh-CN`
- Categories: `other`
- Maintainers: `CaoMeiYouRen`
- Source Location: `search.ts`
- Source Module: `() => import('@/routes/bing/search.ts')`

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
  "location": "search.ts",
  "maintainers": [
    "CaoMeiYouRen"
  ],
  "module": "() => import('@/routes/bing/search.ts')",
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
  "url": "cn.bing.com/"
}
```
