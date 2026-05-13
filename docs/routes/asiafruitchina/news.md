# 亚洲水果 - 行业资讯

## Coverage
`index-only`

## Route
- Namespace: `asiafruitchina`
- Namespace Name: `亚洲水果`
- Route Path: `/news`
- Route Name: `行业资讯`
- Example: `/asiafruitchina/news`
- URL: `asiafruitchina.net`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/asiafruitchina/news.ts')`

## Description
_None_

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
  - `asiafruitchina.net/category/news`
- `target`: `/asiafruitchina/news`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/asiafruitchina/news",
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
    "nczitzk"
  ],
  "module": "() => import('@/routes/asiafruitchina/news.ts')",
  "name": "行业资讯",
  "path": "/news",
  "radar": [
    {
      "source": [
        "asiafruitchina.net/category/news"
      ],
      "target": "/asiafruitchina/news"
    }
  ],
  "url": "asiafruitchina.net",
  "view": 0
}
```
