# 巴哈姆特電玩資訊站 - 本板推薦

## Coverage
`index-only`

## Route
- Namespace: `gamer`
- Namespace Name: `巴哈姆特電玩資訊站`
- Route Path: `/hot/:bsn`
- Route Name: `本板推薦`
- Example: `/gamer/hot/47157`
- URL: `acg.gamer.com.tw`
- Language: `zh-TW`
- Categories: `anime`
- Maintainers: `nczitzk, TonyRL, kennyfong19931`
- Source Location: `hot.ts`
- Source Module: `() => import('@/routes/gamer/hot.ts')`

## Description
_None_

## Parameters
- `bsn`: 板塊 id，在 URL 可以找到


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
    "anime"
  ],
  "example": "/gamer/hot/47157",
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
    "nczitzk",
    "TonyRL",
    "kennyfong19931"
  ],
  "module": "() => import('@/routes/gamer/hot.ts')",
  "name": "本板推薦",
  "parameters": {
    "bsn": "板塊 id，在 URL 可以找到"
  },
  "path": "/hot/:bsn",
  "view": 0
}
```
