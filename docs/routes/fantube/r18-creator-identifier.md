# FANTUBE - User Posts

## Coverage
`index-only`

## Route
- Namespace: `fantube`
- Namespace Name: `FANTUBE`
- Route Path: `/r18/creator/:identifier`
- Route Name: `User Posts`
- Example: `/fantube/r18/creator/miyuu`
- URL: `www.fantube.tokyo`
- Language: `ja`
- Categories: `multimedia`
- Maintainers: `TonyRL`
- Source Location: `creator.tsx`
- Source Module: `() => import('@/routes/fantube/creator.tsx')`

## Description
_None_

## Parameters
- `identifier`: User handle


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
  - `www.fantube.tokyo/r18/creator/:identifier`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/fantube/r18/creator/miyuu",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "creator.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/fantube/creator.tsx')",
  "name": "User Posts",
  "parameters": {
    "identifier": "User handle"
  },
  "path": "/r18/creator/:identifier",
  "radar": [
    {
      "source": [
        "www.fantube.tokyo/r18/creator/:identifier"
      ]
    }
  ]
}
```
