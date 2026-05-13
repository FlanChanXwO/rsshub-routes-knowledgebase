# 消费者报道 - 要闻

## Coverage
`index-only`

## Route
- Namespace: `ccreports`
- Namespace Name: `消费者报道`
- Route Path: `/article`
- Route Name: `要闻`
- Example: `/ccreports/article`
- URL: `www.ccreports.com.cn/`
- Language: `zh-CN`
- Categories: `shopping`
- Maintainers: `EsuRt, Fatpandac`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/ccreports/index.ts')`

## Description
_None_

## Parameters
_None_


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
  - `www.ccreports.com.cn/`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "example": "/ccreports/article",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "EsuRt",
    "Fatpandac"
  ],
  "module": "() => import('@/routes/ccreports/index.ts')",
  "name": "要闻",
  "parameters": {},
  "path": "/article",
  "radar": [
    {
      "source": [
        "www.ccreports.com.cn/"
      ]
    }
  ],
  "url": "www.ccreports.com.cn/"
}
```
