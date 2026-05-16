# Furaffinity - User's Watching List

## Coverage
`index-only`

## Route
- Namespace: `furaffinity`
- Namespace Name: `Furaffinity`
- Route Path: `/furaffinity/watching/:username`
- Route Name: `User's Watching List`
- Example: `/furaffinity/watching/fender`
- URL: `furaffinity.net`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `TigerCubDen, SkyNetX007`
- Source Location: `watching.ts`
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
  - `furaffinity.net/watchlist/by/:username`
- `target`: `/watching/:username`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/furaffinity/watching/fender",
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
  "location": "watching.ts",
  "maintainers": [
    "TigerCubDen",
    "SkyNetX007"
  ],
  "name": "User's Watching List",
  "parameters": {
    "username": "Username, can find in userpage"
  },
  "path": "/watching/:username",
  "radar": [
    {
      "source": [
        "furaffinity.net/watchlist/by/:username"
      ],
      "target": "/watching/:username"
    }
  ],
  "topFeeds": [],
  "url": "furaffinity.net"
}
```
