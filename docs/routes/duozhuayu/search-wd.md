# 多抓鱼 - 搜索结果

## Coverage
`index-only`

## Route
- Namespace: `duozhuayu`
- Namespace Name: `多抓鱼`
- Route Path: `/search/:wd`
- Route Name: `搜索结果`
- Example: `/duozhuayu/search/JavaScript`
- URL: `duozhuayu.com`
- Language: `zh-CN`
- Categories: `shopping`
- Maintainers: `fengkx`
- Source Location: `search.tsx`
- Source Module: `() => import('@/routes/duozhuayu/search.tsx')`

## Description
_None_

## Parameters
- `wd`: 搜索关键词


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
  - `duozhuayu.com/search/book/:wd`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "example": "/duozhuayu/search/JavaScript",
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
    "fengkx"
  ],
  "module": "() => import('@/routes/duozhuayu/search.tsx')",
  "name": "搜索结果",
  "parameters": {
    "wd": "搜索关键词"
  },
  "path": "/search/:wd",
  "radar": [
    {
      "source": [
        "duozhuayu.com/search/book/:wd"
      ]
    }
  ]
}
```
