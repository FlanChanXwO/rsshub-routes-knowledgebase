# 新华每日电讯 - 今日

## Coverage
`index-only`

## Route
- Namespace: `mrdx`
- Namespace Name: `新华每日电讯`
- Route Path: `/today`
- Route Name: `今日`
- Example: `/mrdx/today`
- URL: `mrdx.cn*`
- Language: `zh-CN`
- Categories: `traditional-media`
- Maintainers: `Dustin-Jiang`
- Source Location: `daily.ts`
- Source Module: `() => import('@/routes/mrdx/daily.ts')`

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
  - `mrdx.cn*`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/mrdx/today",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "daily.ts",
  "maintainers": [
    "Dustin-Jiang"
  ],
  "module": "() => import('@/routes/mrdx/daily.ts')",
  "name": "今日",
  "parameters": {},
  "path": "/today",
  "radar": [
    {
      "source": [
        "mrdx.cn*"
      ]
    }
  ],
  "url": "mrdx.cn*"
}
```
