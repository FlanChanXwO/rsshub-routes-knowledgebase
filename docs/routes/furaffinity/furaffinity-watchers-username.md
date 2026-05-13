# Furaffinity - User's Watcher List

## Coverage
`index-only`

## Route
- Namespace: `furaffinity`
- Namespace Name: `Furaffinity`
- Route Path: `/furaffinity/watchers/:username`
- Route Name: `User's Watcher List`
- Example: `/furaffinity/watchers/fender`
- URL: `furaffinity.net`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `TigerCubDen, SkyNetX007`
- Source Location: `watchers.ts`
- Source Module: `_None_`

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
  - `furaffinity.net/watchlist/to/:username`
- `target`: `/watchers/:username`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/furaffinity/watchers/fender",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "watchers.ts",
  "maintainers": [
    "TigerCubDen",
    "SkyNetX007"
  ],
  "name": "User's Watcher List",
  "parameters": {
    "username": "Username, can find in userpage"
  },
  "path": "/watchers/:username",
  "radar": [
    {
      "source": [
        "furaffinity.net/watchlist/to/:username"
      ],
      "target": "/watchers/:username"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "furaffinity.net"
}
```
