# Furaffinity - Status

## Coverage
`index-only`

## Route
- Namespace: `furaffinity`
- Namespace Name: `Furaffinity`
- Route Path: `/status`
- Route Name: `Status`
- Example: `/furaffinity/status`
- URL: `furaffinity.net`
- Language: `en`
- Categories: `social-media`
- Maintainers: `TigerCubDen, SkyNetX007`
- Source Location: `status.ts`
- Source Module: `() => import('@/routes/furaffinity/status.ts')`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `furaffinity.net`
- `target`: `/`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/furaffinity/status",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "status.ts",
  "maintainers": [
    "TigerCubDen",
    "SkyNetX007"
  ],
  "module": "() => import('@/routes/furaffinity/status.ts')",
  "name": "Status",
  "parameters": {},
  "path": "/status",
  "radar": [
    {
      "source": [
        "furaffinity.net"
      ],
      "target": "/"
    }
  ],
  "url": "furaffinity.net"
}
```
