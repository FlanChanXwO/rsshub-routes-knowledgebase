# Pikabu - User

## Coverage
`index-only`

## Route
- Namespace: `pikabu`
- Namespace Name: `Pikabu`
- Route Path: `/user/:name`
- Route Name: `User`
- Example: `/pikabu/user/@bula.dragon`
- URL: `pikabu.ru`
- Language: `ru`
- Categories: `bbs`
- Maintainers: `TonyRL`
- Source Location: `user.ts`
- Source Module: `() => import('@/routes/pikabu/user.ts')`

## Description
_None_

## Parameters
- `name`: User name


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
  - `pikabu.ru/:name`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/pikabu/user/@bula.dragon",
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
  "module": "() => import('@/routes/pikabu/user.ts')",
  "name": "User",
  "parameters": {
    "name": "User name"
  },
  "path": "/user/:name",
  "radar": [
    {
      "source": [
        "pikabu.ru/:name"
      ]
    }
  ]
}
```
