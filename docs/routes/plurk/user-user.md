# Plurk - User

## Coverage
`index-only`

## Route
- Namespace: `plurk`
- Namespace Name: `Plurk`
- Route Path: `/user/:user`
- Route Name: `User`
- Example: `/plurk/user/plurkoffice`
- URL: `plurk.com`
- Language: `en`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `user.ts`
- Source Module: `() => import('@/routes/plurk/user.ts')`

## Description
_None_

## Parameters
- `user`: User ID, can be found in URL


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
    "social-media"
  ],
  "example": "/plurk/user/plurkoffice",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "user.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/plurk/user.ts')",
  "name": "User",
  "parameters": {
    "user": "User ID, can be found in URL"
  },
  "path": "/user/:user",
  "view": 1
}
```
