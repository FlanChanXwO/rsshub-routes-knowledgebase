# GETTR - User timeline

## Coverage
`index-only`

## Route
- Namespace: `gettr`
- Namespace Name: `GETTR`
- Route Path: `/user/:id`
- Route Name: `User timeline`
- Example: `/gettr/user/jasonmillerindc`
- URL: `gettr.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `user.tsx`
- Source Module: `() => import('@/routes/gettr/user.tsx')`

## Description
_None_

## Parameters
- `id`: User id


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
  - `gettr.com/user/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/gettr/user/jasonmillerindc",
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
    "TonyRL"
  ],
  "module": "() => import('@/routes/gettr/user.tsx')",
  "name": "User timeline",
  "parameters": {
    "id": "User id"
  },
  "path": "/user/:id",
  "radar": [
    {
      "source": [
        "gettr.com/user/:id"
      ]
    }
  ],
  "view": 1
}
```
