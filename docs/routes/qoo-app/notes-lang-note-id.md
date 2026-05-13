# QooApp - Note Comments

## Coverage
`index-only`

## Route
- Namespace: `qoo-app`
- Namespace Name: `QooApp`
- Route Path: `/notes/:lang?/note/:id`
- Route Name: `Note Comments`
- Example: `/qoo-app/notes/en/note/2329113`
- URL: `apps.qoo-app.com`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `TonyRL`
- Source Location: `notes/note.ts`
- Source Module: `() => import('@/routes/qoo-app/notes/note.ts')`

## Description
_None_

## Parameters
- `lang`: Language, see the table above, empty means `中文`
- `id`: Note ID, can be found in URL


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
  "example": "/qoo-app/notes/en/note/2329113",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "notes/note.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/qoo-app/notes/note.ts')",
  "name": "Note Comments",
  "parameters": {
    "id": "Note ID, can be found in URL",
    "lang": "Language, see the table above, empty means `中文`"
  },
  "path": "/notes/:lang?/note/:id"
}
```
