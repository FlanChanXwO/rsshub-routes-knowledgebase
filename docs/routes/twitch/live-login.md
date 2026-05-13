# Twitch - Live

## Coverage
`index-only`

## Route
- Namespace: `twitch`
- Namespace Name: `Twitch`
- Route Path: `/live/:login`
- Route Name: `Live`
- Example: `/twitch/live/riotgames`
- URL: `www.twitch.tv`
- Language: `en`
- Categories: `live`
- Maintainers: `hoilc`
- Source Location: `live.ts`
- Source Module: `() => import('@/routes/twitch/live.ts')`

## Description
_None_

## Parameters
- `login`: Twitch username


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
    "live"
  ],
  "example": "/twitch/live/riotgames",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "live.ts",
  "maintainers": [
    "hoilc"
  ],
  "module": "() => import('@/routes/twitch/live.ts')",
  "name": "Live",
  "parameters": {
    "login": "Twitch username"
  },
  "path": "/live/:login",
  "view": 5
}
```
