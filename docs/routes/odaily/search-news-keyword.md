# Odaily 星球日报 - 搜索快讯

## Coverage
`index-only`

## Route
- Namespace: `odaily`
- Namespace Name: `Odaily 星球日报`
- Route Path: `/search/news/:keyword`
- Route Name: `搜索快讯`
- Example: `/odaily/search/news/RSS3`
- URL: `odaily.news`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `snowraincloud`
- Source Location: `search-news.ts`
- Source Module: `() => import('@/routes/odaily/search-news.ts')`

## Description
_None_

## Parameters
- `keyword`: 搜索关键字


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
  - `0daily.com/search/:keyword`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/odaily/search/news/RSS3",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "search-news.ts",
  "maintainers": [
    "snowraincloud"
  ],
  "module": "() => import('@/routes/odaily/search-news.ts')",
  "name": "搜索快讯",
  "parameters": {
    "keyword": "搜索关键字"
  },
  "path": "/search/news/:keyword",
  "radar": [
    {
      "source": [
        "0daily.com/search/:keyword"
      ]
    }
  ]
}
```
