# Mirror - User

## Coverage
`index-only`

## Route
- Namespace: `mirror`
- Namespace Name: `Mirror`
- Route Path: `/:id`
- Route Name: `User`
- Example: `/mirror/tingfei.eth`
- URL: `mirror.xyz`
- Language: `en`
- Categories: `new-media`
- Maintainers: `fifteen42, rde9, nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/mirror/index.ts')`

## Description
_None_

## Parameters
- `id`: user id


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
    "new-media"
  ],
  "example": "/mirror/tingfei.eth",
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
    "fifteen42",
    "rde9",
    "nczitzk"
  ],
  "module": "() => import('@/routes/mirror/index.ts')",
  "name": "User",
  "parameters": {
    "id": "user id"
  },
  "path": "/:id"
}
```
