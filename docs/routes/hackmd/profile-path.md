# HackMD - Profile

## Coverage
`index-only`

## Route
- Namespace: `hackmd`
- Namespace Name: `HackMD`
- Route Path: `/profile/:path`
- Route Name: `Profile`
- Example: `/hackmd/profile/hackmd`
- URL: `hackmd.io`
- Language: `en`
- Categories: `programming`
- Maintainers: `Yukaii, kaiix`
- Source Location: `profile.ts`
- Source Module: `() => import('@/routes/hackmd/profile.ts')`

## Description
_None_

## Parameters
- `path`: userpath or teampath


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
    "programming"
  ],
  "example": "/hackmd/profile/hackmd",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "profile.ts",
  "maintainers": [
    "Yukaii",
    "kaiix"
  ],
  "module": "() => import('@/routes/hackmd/profile.ts')",
  "name": "Profile",
  "parameters": {
    "path": "userpath or teampath"
  },
  "path": "/profile/:path"
}
```
