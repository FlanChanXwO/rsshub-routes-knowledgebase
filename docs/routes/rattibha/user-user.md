# Rattibha - User Threads

## Coverage
`index-only`

## Route
- Namespace: `rattibha`
- Namespace Name: `Rattibha`
- Route Path: `/user/:user`
- Route Name: `User Threads`
- Example: `/rattibha/user/elonmusk`
- URL: `rattibha.com`
- Language: `en`
- Categories: `social-media`
- Maintainers: `yshalsager`
- Source Location: `user.tsx`
- Source Module: `() => import('@/routes/rattibha/user.tsx')`

## Description
_None_

## Parameters
- `user`: Twitter username, without @


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
  - `rattibha.com/:user`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/rattibha/user/elonmusk",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "user.tsx",
  "maintainers": [
    "yshalsager"
  ],
  "module": "() => import('@/routes/rattibha/user.tsx')",
  "name": "User Threads",
  "parameters": {
    "user": "Twitter username, without @"
  },
  "path": "/user/:user",
  "radar": [
    {
      "source": [
        "rattibha.com/:user"
      ]
    }
  ]
}
```
