# BT影视 - BTBTLA | 指定剧名

## Coverage
`index-only`

## Route
- Namespace: `btbtla`
- Namespace Name: `BT影视`
- Route Path: `/detail/:name`
- Route Name: `BTBTLA | 指定剧名`
- Example: `/btbtla/detail/雍正王朝`
- URL: `www.btbtla.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `Hermes1030`
- Source Location: `detail.ts`
- Source Module: `() => import('@/routes/btbtla/detail.ts')`

## Description
_None_

## Parameters
- `name`: 电影 | 电视剧名称


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: true
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/btbtla/detail/雍正王朝",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": true,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "detail.ts",
  "maintainers": [
    "Hermes1030"
  ],
  "module": "() => import('@/routes/btbtla/detail.ts')",
  "name": "BTBTLA | 指定剧名",
  "parameters": {
    "name": "电影 | 电视剧名称"
  },
  "path": "/detail/:name"
}
```
