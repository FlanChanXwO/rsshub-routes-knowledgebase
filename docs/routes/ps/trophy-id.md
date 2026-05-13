# PlayStation Store - PlayStation Network user trophy

## Coverage
`index-only`

## Route
- Namespace: `ps`
- Namespace Name: `PlayStation Store`
- Route Path: `/trophy/:id`
- Route Name: `PlayStation Network user trophy`
- Example: `/ps/trophy/DIYgod_`
- URL: `www.playstation.com`
- Language: `en`
- Categories: `game`
- Maintainers: `DIYgod`
- Source Location: `trophy.ts`
- Source Module: `() => import('@/routes/ps/trophy.ts')`

## Description
_None_

## Parameters
- `id`: User ID


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/ps/trophy/DIYgod_",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "trophy.ts",
  "maintainers": [
    "DIYgod"
  ],
  "module": "() => import('@/routes/ps/trophy.ts')",
  "name": "PlayStation Network user trophy",
  "parameters": {
    "id": "User ID"
  },
  "path": "/trophy/:id"
}
```
