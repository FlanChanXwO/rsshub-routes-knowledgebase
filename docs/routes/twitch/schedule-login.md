# Twitch - Stream Schedule

## Coverage
`index-only`

## Route
- Namespace: `twitch`
- Namespace Name: `Twitch`
- Route Path: `/schedule/:login`
- Route Name: `Stream Schedule`
- Example: `/twitch/schedule/riotgames`
- URL: `www.twitch.tv`
- Language: `en`
- Categories: `live`
- Maintainers: `hoilc`
- Source Location: `schedule.ts`
- Source Module: `() => import('@/routes/twitch/schedule.ts')`

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
### Rule 1
- `source`:
  - `www.twitch.tv/:login/schedule`

## Raw JSON
```json
{
  "categories": [
    "live"
  ],
  "example": "/twitch/schedule/riotgames",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "schedule.ts",
  "maintainers": [
    "hoilc"
  ],
  "module": "() => import('@/routes/twitch/schedule.ts')",
  "name": "Stream Schedule",
  "parameters": {
    "login": "Twitch username"
  },
  "path": "/schedule/:login",
  "radar": [
    {
      "source": [
        "www.twitch.tv/:login/schedule"
      ]
    }
  ]
}
```
