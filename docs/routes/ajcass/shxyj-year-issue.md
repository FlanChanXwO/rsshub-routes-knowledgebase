# 社科期刊网 - 社会学研究

## Coverage
`index-only`

## Route
- Namespace: `ajcass`
- Namespace Name: `社科期刊网`
- Route Path: `/shxyj/:year?/:issue?`
- Route Name: `社会学研究`
- Example: `/ajcass/shxyj/2024/1`
- URL: `ajcass.com`
- Language: `zh-CN`
- Categories: `journal`
- Maintainers: `CNYoki`
- Source Location: `shxyj.ts`
- Source Module: `() => import('@/routes/ajcass/shxyj.ts')`

## Description
_None_

## Parameters
- `year`: Year of the issue, `null` for the lastest
- `issue`: Issue number, `null` for the lastest


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/ajcass/shxyj/2024/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "shxyj.ts",
  "maintainers": [
    "CNYoki"
  ],
  "module": "() => import('@/routes/ajcass/shxyj.ts')",
  "name": "社会学研究",
  "parameters": {
    "issue": "Issue number, `null` for the lastest",
    "year": "Year of the issue, `null` for the lastest"
  },
  "path": "/shxyj/:year?/:issue?"
}
```
