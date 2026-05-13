# Furaffinity - Browse

## Coverage
`index-only`

## Route
- Namespace: `furaffinity`
- Namespace Name: `Furaffinity`
- Route Path: `/browse/:mode?`
- Route Name: `Browse`
- Example: `/furaffinity/browse/nsfw`
- URL: `furaffinity.net`
- Language: `en`
- Categories: `social-media`
- Maintainers: `TigerCubDen, SkyNetX007`
- Source Location: `browse.ts`
- Source Module: `() => import('@/routes/furaffinity/browse.ts')`

## Description
_None_

## Parameters
- `mode`: R18 content toggle, default value is sfw, options are sfw, nsfw


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
- `target`: `/browse`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/furaffinity/browse/nsfw",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "browse.ts",
  "maintainers": [
    "TigerCubDen",
    "SkyNetX007"
  ],
  "module": "() => import('@/routes/furaffinity/browse.ts')",
  "name": "Browse",
  "parameters": {
    "mode": "R18 content toggle, default value is sfw, options are sfw, nsfw"
  },
  "path": "/browse/:mode?",
  "radar": [
    {
      "source": [
        "furaffinity.net"
      ],
      "target": "/browse"
    }
  ],
  "url": "furaffinity.net"
}
```
