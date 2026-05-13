# Furaffinity - Shouts

## Coverage
`index-only`

## Route
- Namespace: `furaffinity`
- Namespace Name: `Furaffinity`
- Route Path: `/shouts/:username`
- Route Name: `Shouts`
- Example: `/furaffinity/shouts/fender`
- URL: `furaffinity.net`
- Language: `en`
- Categories: `social-media`
- Maintainers: `TigerCubDen, SkyNetX007`
- Source Location: `shouts.ts`
- Source Module: `() => import('@/routes/furaffinity/shouts.ts')`

## Description
_None_

## Parameters
- `username`: Username, can find in userpage


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
  - `furaffinity.net/user/:username`
- `target`: `/shouts/:username`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/furaffinity/shouts/fender",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "shouts.ts",
  "maintainers": [
    "TigerCubDen",
    "SkyNetX007"
  ],
  "module": "() => import('@/routes/furaffinity/shouts.ts')",
  "name": "Shouts",
  "parameters": {
    "username": "Username, can find in userpage"
  },
  "path": "/shouts/:username",
  "radar": [
    {
      "source": [
        "furaffinity.net/user/:username"
      ],
      "target": "/shouts/:username"
    }
  ],
  "url": "furaffinity.net"
}
```
