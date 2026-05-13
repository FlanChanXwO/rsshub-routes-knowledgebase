# 百度 - 搜索

## Coverage
`index-only`

## Route
- Namespace: `baidu`
- Namespace Name: `百度`
- Route Path: `/search/:keyword`
- Route Name: `搜索`
- Example: `/baidu/search/rss`
- URL: `www.baidu.com`
- Language: `zh-CN`
- Categories: `other`
- Maintainers: `CaoMeiYouRen`
- Source Location: `search.tsx`
- Source Module: `() => import('@/routes/baidu/search.tsx')`

## Description
_None_

## Parameters
- `keyword`: 搜索关键词


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
    "other"
  ],
  "example": "/baidu/search/rss",
  "features": {
    "antiCrawler": true,
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
  "module": "() => import('@/routes/baidu/search.tsx')",
  "name": "搜索",
  "parameters": {
    "keyword": "搜索关键词"
  },
  "path": "/search/:keyword"
}
```
