# QooApp - User Notes

## Coverage
`index-only`

## Route
- Namespace: `qoo-app`
- Namespace Name: `QooApp`
- Route Path: `/notes/:lang?/user/:uid`
- Route Name: `User Notes`
- Example: `/qoo-app/notes/en/user/35399143`
- URL: `apps.qoo-app.com`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `TonyRL`
- Source Location: `notes/user.ts`
- Source Module: `() => import('@/routes/qoo-app/notes/user.ts')`

## Description
_None_

## Parameters
- `lang`: Language, see the table above, empty means `中文`
- `uid`: User ID, can be found in URL


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
  "example": "/qoo-app/notes/en/user/35399143",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "notes/user.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/qoo-app/notes/user.ts')",
  "name": "User Notes",
  "parameters": {
    "lang": "Language, see the table above, empty means `中文`",
    "uid": "User ID, can be found in URL"
  },
  "path": "/notes/:lang?/user/:uid"
}
```
