# 财新博客 - 首页新闻

## Coverage
`index-only`

## Route
- Namespace: `caixin`
- Namespace Name: `财新博客`
- Route Path: `/article`
- Route Name: `首页新闻`
- Example: `/caixin/article`
- URL: `caixin.com/`
- Language: `zh-CN`
- Categories: `traditional-media`
- Maintainers: `EsuRt`
- Source Location: `article.ts`
- Source Module: `() => import('@/routes/caixin/article.ts')`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: true
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `caixin.com/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/caixin/article",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportScihub": false
  },
  "location": "article.ts",
  "maintainers": [
    "EsuRt"
  ],
  "module": "() => import('@/routes/caixin/article.ts')",
  "name": "首页新闻",
  "parameters": {},
  "path": "/article",
  "radar": [
    {
      "source": [
        "caixin.com/"
      ]
    }
  ],
  "url": "caixin.com/"
}
```
