# Furaffinity - Userpage

## Coverage
`index-only`

## Route
- Namespace: `furaffinity`
- Namespace Name: `Furaffinity`
- Route Path: `/user/:username`
- Route Name: `Userpage`
- Example: `/furaffinity/user/fender/nsfw`
- URL: `furaffinity.net`
- Language: `en`
- Categories: `social-media`
- Maintainers: `TigerCubDen, SkyNetX007`
- Source Location: `user.ts`
- Source Module: `() => import('@/routes/furaffinity/user.ts')`

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
- `target`: `/user/:username`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/furaffinity/user/fender/nsfw",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "user.ts",
  "maintainers": [
    "TigerCubDen",
    "SkyNetX007"
  ],
  "module": "() => import('@/routes/furaffinity/user.ts')",
  "name": "Userpage",
  "parameters": {
    "username": "Username, can find in userpage"
  },
  "path": "/user/:username",
  "radar": [
    {
      "source": [
        "furaffinity.net/user/:username"
      ],
      "target": "/user/:username"
    }
  ],
  "url": "furaffinity.net"
}
```
