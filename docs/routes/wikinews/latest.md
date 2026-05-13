# 维基新闻 - 最新新闻

## Coverage
`index-only`

## Route
- Namespace: `wikinews`
- Namespace Name: `维基新闻`
- Route Path: `/latest`
- Route Name: `最新新闻`
- Example: `/wikinews/latest`
- URL: `zh.wikinews.org`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `KotoriK`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/wikinews/index.ts')`

## Description
根据维基新闻的[sitemap](https://zh.wikinews.org/wiki/Special:%E6%96%B0%E9%97%BB%E8%AE%A2%E9%98%85)获取新闻全文。目前仅支持中文维基新闻。

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
  - `zh.wikinews.org/wiki/Special:新闻订阅`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "根据维基新闻的[sitemap](https://zh.wikinews.org/wiki/Special:%E6%96%B0%E9%97%BB%E8%AE%A2%E9%98%85)获取新闻全文。目前仅支持中文维基新闻。",
  "example": "/wikinews/latest",
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
    "KotoriK"
  ],
  "module": "() => import('@/routes/wikinews/index.ts')",
  "name": "最新新闻",
  "parameters": {},
  "path": "/latest",
  "radar": [
    {
      "source": [
        "zh.wikinews.org/wiki/Special:新闻订阅"
      ]
    }
  ]
}
```
