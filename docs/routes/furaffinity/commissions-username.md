# Furaffinity - Commissions

## Coverage
`index-only`

## Route
- Namespace: `furaffinity`
- Namespace Name: `Furaffinity`
- Route Path: `/commissions/:username`
- Route Name: `Commissions`
- Example: `/furaffinity/commissions/fender`
- URL: `furaffinity.net`
- Language: `en`
- Categories: `social-media`
- Maintainers: `TigerCubDen, SkyNetX007`
- Source Location: `commissions.ts`
- Source Module: `() => import('@/routes/furaffinity/commissions.ts')`

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
  - `furaffinity.net/commissions/:username`
- `target`: `/commissions/:username`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/furaffinity/commissions/fender",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "commissions.ts",
  "maintainers": [
    "TigerCubDen",
    "SkyNetX007"
  ],
  "module": "() => import('@/routes/furaffinity/commissions.ts')",
  "name": "Commissions",
  "parameters": {
    "username": "Username, can find in userpage"
  },
  "path": "/commissions/:username",
  "radar": [
    {
      "source": [
        "furaffinity.net/commissions/:username"
      ],
      "target": "/commissions/:username"
    }
  ],
  "url": "furaffinity.net"
}
```
