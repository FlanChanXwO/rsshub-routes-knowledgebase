# Spotify - Personal Top Tracks

## Coverage
`index-only`

## Route
- Namespace: `spotify`
- Namespace Name: `Spotify`
- Route Path: `/top/tracks`
- Route Name: `Personal Top Tracks`
- Example: `/spotify/top/tracks`
- URL: `open.spotify.com/`
- Language: `en`
- Categories: `multimedia`
- Maintainers: `outloudvi`
- Source Location: `tracks-top.ts`
- Source Module: `() => import('@/routes/spotify/tracks-top.ts')`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: [{"description": "", "name": "SPOTIFY_CLIENT_ID"}, {"description": "", "name": "SPOTIFY_CLIENT_SECRET"}, {"description": "", "name": "SPOTIFY_REFRESHTOKEN"}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `open.spotify.com/`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/spotify/top/tracks",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "",
        "name": "SPOTIFY_CLIENT_ID"
      },
      {
        "description": "",
        "name": "SPOTIFY_CLIENT_SECRET"
      },
      {
        "description": "",
        "name": "SPOTIFY_REFRESHTOKEN"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "tracks-top.ts",
  "maintainers": [
    "outloudvi"
  ],
  "module": "() => import('@/routes/spotify/tracks-top.ts')",
  "name": "Personal Top Tracks",
  "parameters": {},
  "path": "/top/tracks",
  "radar": [
    {
      "source": [
        "open.spotify.com/"
      ]
    }
  ],
  "url": "open.spotify.com/"
}
```
