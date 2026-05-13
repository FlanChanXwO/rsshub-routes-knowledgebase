# Meteor - 看板

## Coverage
`index-only`

## Route
- Namespace: `meteor`
- Namespace Name: `Meteor`
- Route Path: `/:board?`
- Route Name: `看板`
- Example: `/meteor/all`
- URL: `meteor.today`
- Language: `en`
- Categories: `bbs`
- Maintainers: `TonyRL`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/meteor/index.ts')`

## Description
_None_

## Parameters
- `board`: 看板 ID 或簡稱，可在 URL 或下方路由找到，預設為 `all`


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
    "bbs"
  ],
  "example": "/meteor/all",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/meteor/index.ts')",
  "name": "看板",
  "parameters": {
    "board": "看板 ID 或簡稱，可在 URL 或下方路由找到，預設為 `all`"
  },
  "path": "/:board?"
}
```
