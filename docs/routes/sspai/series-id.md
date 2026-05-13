# 少数派 sspai - 付费专栏文章更新

## Coverage
`index-only`

## Route
- Namespace: `sspai`
- Namespace Name: `少数派 sspai`
- Route Path: `/series/:id`
- Route Name: `付费专栏文章更新`
- Example: `/sspai/series/77`
- URL: `sspai.com/series`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `series-update.ts`
- Source Module: `() => import('@/routes/sspai/series-update.ts')`

## Description
_None_

## Parameters
- `id`: 专栏 id


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
  - `sspai.com/series/:id`
  - `sspai.com/series/:id/list`
  - `sspai.com/series/:id/metadata`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/sspai/series/77",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "series-update.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/sspai/series-update.ts')",
  "name": "付费专栏文章更新",
  "parameters": {
    "id": "专栏 id"
  },
  "path": "/series/:id",
  "radar": [
    {
      "source": [
        "sspai.com/series/:id",
        "sspai.com/series/:id/list",
        "sspai.com/series/:id/metadata"
      ]
    }
  ],
  "url": "sspai.com/series"
}
```
