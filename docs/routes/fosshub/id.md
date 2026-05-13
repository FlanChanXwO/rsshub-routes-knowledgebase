# FossHub - Software Update

## Coverage
`index-only`

## Route
- Namespace: `fosshub`
- Namespace Name: `FossHub`
- Route Path: `/:id`
- Route Name: `Software Update`
- Example: `/fosshub/qBittorrent`
- URL: `fosshub.com`
- Language: `en`
- Categories: `program-update`
- Maintainers: `nczitzk`
- Source Location: `index.tsx`
- Source Module: `() => import('@/routes/fosshub/index.tsx')`

## Description
_None_

## Parameters
- `id`: Software id, can be found in URL


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
    "program-update"
  ],
  "example": "/fosshub/qBittorrent",
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
    "nczitzk"
  ],
  "module": "() => import('@/routes/fosshub/index.tsx')",
  "name": "Software Update",
  "parameters": {
    "id": "Software id, can be found in URL"
  },
  "path": "/:id"
}
```
