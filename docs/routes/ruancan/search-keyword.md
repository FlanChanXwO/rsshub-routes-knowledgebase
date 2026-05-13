# 软餐 - 搜索

## Coverage
`index-only`

## Route
- Namespace: `ruancan`
- Namespace Name: `软餐`
- Route Path: `/search/:keyword?`
- Route Name: `搜索`
- Example: `/ruancan/search/Windows`
- URL: `ruancan.com/`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `None`
- Source Location: `search.ts`
- Source Module: `() => import('@/routes/ruancan/search.ts')`

## Description
_None_

## Parameters
- `keyword`: 关键字，默认为空


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `ruancan.com/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/ruancan/search/Windows",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "search.ts",
  "maintainers": [],
  "module": "() => import('@/routes/ruancan/search.ts')",
  "name": "搜索",
  "parameters": {
    "keyword": "关键字，默认为空"
  },
  "path": "/search/:keyword?",
  "radar": [
    {
      "source": [
        "ruancan.com/"
      ],
      "target": ""
    }
  ],
  "url": "ruancan.com/"
}
```
