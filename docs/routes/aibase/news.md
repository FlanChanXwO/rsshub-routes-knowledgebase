# AIbase - 资讯

## Coverage
`index-only`

## Route
- Namespace: `aibase`
- Namespace Name: `AIbase`
- Route Path: `/news`
- Route Name: `资讯`
- Example: `/aibase/news`
- URL: `www.aibase.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `zreo0`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/aibase/news.ts')`

## Description
获取 AI 资讯列表

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.aibase.com/zh/news`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "获取 AI 资讯列表",
  "example": "/aibase/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "news.ts",
  "maintainers": [
    "zreo0"
  ],
  "module": "() => import('@/routes/aibase/news.ts')",
  "name": "资讯",
  "path": "/news",
  "radar": [
    {
      "source": [
        "www.aibase.com/zh/news"
      ],
      "target": "/news"
    }
  ],
  "url": "www.aibase.com"
}
```
