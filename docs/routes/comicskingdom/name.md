# Comics Kingdom - Archive

## Coverage
`index-only`

## Route
- Namespace: `comicskingdom`
- Namespace Name: `Comics Kingdom`
- Route Path: `/:name`
- Route Name: `Archive`
- Example: `/comicskingdom/pardon-my-planet`
- URL: `comicskingdom.com`
- Language: `en`
- Categories: `anime`
- Maintainers: `stjohnjohnson`
- Source Location: `index.tsx`
- Source Module: `() => import('@/routes/comicskingdom/index.tsx')`

## Description
_None_

## Parameters
- `name`: URL path of the strip on comicskingdom.com


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
  - `comicskingdom.com/:name/*`
  - `comicskingdom.com/:name`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/comicskingdom/pardon-my-planet",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.tsx",
  "maintainers": [
    "stjohnjohnson"
  ],
  "module": "() => import('@/routes/comicskingdom/index.tsx')",
  "name": "Archive",
  "parameters": {
    "name": "URL path of the strip on comicskingdom.com"
  },
  "path": "/:name",
  "radar": [
    {
      "source": [
        "comicskingdom.com/:name/*",
        "comicskingdom.com/:name"
      ]
    }
  ]
}
```
