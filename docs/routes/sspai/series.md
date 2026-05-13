# 少数派 sspai - 最新上架付费专栏

## Coverage
`index-only`

## Route
- Namespace: `sspai`
- Namespace Name: `少数派 sspai`
- Route Path: `/series`
- Route Name: `最新上架付费专栏`
- Example: `/sspai/series`
- URL: `sspai.com/series`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `HenryQW`
- Source Location: `series.ts`
- Source Module: `() => import('@/routes/sspai/series.ts')`

## Description
> 少数派专栏需要付费订阅，RSS 仅做更新提醒，不含付费内容.

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
  - `sspai.com/series`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "> 少数派专栏需要付费订阅，RSS 仅做更新提醒，不含付费内容.",
  "example": "/sspai/series",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "series.ts",
  "maintainers": [
    "HenryQW"
  ],
  "module": "() => import('@/routes/sspai/series.ts')",
  "name": "最新上架付费专栏",
  "parameters": {},
  "path": "/series",
  "radar": [
    {
      "source": [
        "sspai.com/series"
      ]
    }
  ],
  "url": "sspai.com/series"
}
```
