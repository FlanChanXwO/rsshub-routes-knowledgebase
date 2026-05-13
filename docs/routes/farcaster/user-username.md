# Farcaster - Farcaster User

## Coverage
`index-only`

## Route
- Namespace: `farcaster`
- Namespace Name: `Farcaster`
- Route Path: `/user/:username`
- Route Name: `Farcaster User`
- Example: `/farcaster/user/vitalik.eth`
- URL: `www.farcaster.xyz`
- Language: `en`
- Categories: `social-media`
- Maintainers: `DIYgod`
- Source Location: `user.ts`
- Source Module: `() => import('@/routes/farcaster/user.ts')`

## Description
_None_

## Parameters
- `username`: Farcaster username


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
  - `warpcast.com/:username`
- `target`: `/user/:username`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/farcaster/user/vitalik.eth",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "user.ts",
  "maintainers": [
    "DIYgod"
  ],
  "module": "() => import('@/routes/farcaster/user.ts')",
  "name": "Farcaster User",
  "parameters": {
    "username": "Farcaster username"
  },
  "path": "/user/:username",
  "radar": [
    {
      "source": [
        "warpcast.com/:username"
      ],
      "target": "/user/:username"
    }
  ]
}
```
