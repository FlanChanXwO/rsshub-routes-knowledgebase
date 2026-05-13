# 搜狗 - 搜索

## Coverage
`index-only`

## Route
- Namespace: `sogou`
- Namespace Name: `搜狗`
- Route Path: `/search/:keyword`
- Route Name: `搜索`
- Example: `/sogou/search/rss`
- URL: `www.sogou.com`
- Language: `zh-CN`
- Categories: `other`
- Maintainers: `CaoMeiYouRen`
- Source Location: `search.tsx`
- Source Module: `() => import('@/routes/sogou/search.tsx')`

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
_None_

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/sogou/search/rss",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "search.tsx",
  "maintainers": [
    "CaoMeiYouRen"
  ],
  "module": "() => import('@/routes/sogou/search.tsx')",
  "name": "搜索",
  "parameters": {
    "keyword": "搜索关键词"
  },
  "path": "/search/:keyword"
}
```
