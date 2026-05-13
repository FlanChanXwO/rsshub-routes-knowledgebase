# Furaffinity - Gallery

## Coverage
`index-only`

## Route
- Namespace: `furaffinity`
- Namespace Name: `Furaffinity`
- Route Path: `/art/:folder/:username/:mode?`
- Route Name: `Gallery`
- Example: `/furaffinity/art/gallery/fender/nsfw`
- URL: `furaffinity.net`
- Language: `en`
- Categories: `social-media`
- Maintainers: `TigerCubDen, SkyNetX007`
- Source Location: `art.ts`
- Source Module: `() => import('@/routes/furaffinity/art.ts')`

## Description
_None_

## Parameters
- `username`: Username, can find in userpage
- `folder`: Image folders, options are gallery, scraps, favorites
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
  - `furaffinity.net/gallery/:username`
- `target`: `/gallery/:username`
### Rule 2
- `source`:
  - `furaffinity.net/scraps/:username`
- `target`: `/scraps/:username`
### Rule 3
- `source`:
  - `furaffinity.net/favorites/:username`
- `target`: `/favorites/:username`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/furaffinity/art/gallery/fender/nsfw",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "art.ts",
  "maintainers": [
    "TigerCubDen",
    "SkyNetX007"
  ],
  "module": "() => import('@/routes/furaffinity/art.ts')",
  "name": "Gallery",
  "parameters": {
    "folder": "Image folders, options are gallery, scraps, favorites",
    "mode": "R18 content toggle, default value is sfw, options are sfw, nsfw",
    "username": "Username, can find in userpage"
  },
  "path": "/art/:folder/:username/:mode?",
  "radar": [
    {
      "source": [
        "furaffinity.net/gallery/:username"
      ],
      "target": "/gallery/:username"
    },
    {
      "source": [
        "furaffinity.net/scraps/:username"
      ],
      "target": "/scraps/:username"
    },
    {
      "source": [
        "furaffinity.net/favorites/:username"
      ],
      "target": "/favorites/:username"
    }
  ],
  "url": "furaffinity.net"
}
```
