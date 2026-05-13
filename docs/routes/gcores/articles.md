# 机核网 - 文章

## Coverage
`index-only`

## Route
- Namespace: `gcores`
- Namespace Name: `机核网`
- Route Path: `/articles`
- Route Name: `文章`
- Example: `/gcores/articles`
- URL: `www.gcores.com`
- Language: `zh-CN`
- Categories: `game`
- Maintainers: `nczitzk`
- Source Location: `articles.ts`
- Source Module: `() => import('@/routes/gcores/articles.ts')`

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
  - `www.gcores.com/articles`
- `target`: `/gcores/articles`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/gcores/articles",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "articles.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/gcores/articles.ts')",
  "name": "文章",
  "path": "/articles",
  "radar": [
    {
      "source": [
        "www.gcores.com/articles"
      ],
      "target": "/gcores/articles"
    }
  ],
  "url": "www.gcores.com",
  "view": 0
}
```
