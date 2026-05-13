# Furaffinity - Home

## Coverage
`index-only`

## Route
- Namespace: `furaffinity`
- Namespace Name: `Furaffinity`
- Route Path: `/home/:category/:mode?`
- Route Name: `Home`
- Example: `/furaffinity/home/nsfw`
- URL: `furaffinity.net`
- Language: `en`
- Categories: `social-media`
- Maintainers: `TigerCubDen, SkyNetX007`
- Source Location: `home.ts`
- Source Module: `() => import('@/routes/furaffinity/home.ts')`

## Description
_None_

## Parameters
- `category`: Category, default value is artwork, options are artwork, writing, music, crafts
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
- `target`: `/`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/furaffinity/home/nsfw",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "home.ts",
  "maintainers": [
    "TigerCubDen",
    "SkyNetX007"
  ],
  "module": "() => import('@/routes/furaffinity/home.ts')",
  "name": "Home",
  "parameters": {
    "category": "Category, default value is artwork, options are artwork, writing, music, crafts",
    "mode": "R18 content toggle, default value is sfw, options are sfw, nsfw"
  },
  "path": "/home/:category/:mode?",
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
