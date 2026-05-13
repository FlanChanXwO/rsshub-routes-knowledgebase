# 华尔街见闻 - 最热文章

## Coverage
`index-only`

## Route
- Namespace: `wallstreetcn`
- Namespace Name: `华尔街见闻`
- Route Path: `/hot/:period?`
- Route Name: `最热文章`
- Example: `/wallstreetcn/hot`
- URL: `wallstreetcn.com/`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `hot.ts`
- Source Module: `() => import('@/routes/wallstreetcn/hot.ts')`

## Description
_None_

## Parameters
- `period`: 时期，可选 `day` 即 当日 或 `week` 即 当周，默认为当日


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
  - `wallstreetcn.com/`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/wallstreetcn/hot",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "hot.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/wallstreetcn/hot.ts')",
  "name": "最热文章",
  "parameters": {
    "period": "时期，可选 `day` 即 当日 或 `week` 即 当周，默认为当日"
  },
  "path": "/hot/:period?",
  "radar": [
    {
      "source": [
        "wallstreetcn.com/"
      ]
    }
  ],
  "url": "wallstreetcn.com/"
}
```
