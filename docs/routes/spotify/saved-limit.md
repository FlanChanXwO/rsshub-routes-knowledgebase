# Spotify - Personal Saved Tracks

## Coverage
`index-only`

## Route
- Namespace: `spotify`
- Namespace Name: `Spotify`
- Route Path: `/saved/:limit?`
- Route Name: `Personal Saved Tracks`
- Example: `/spotify/saved/50`
- URL: `open.spotify.com/collection/tracks`
- Language: `en`
- Categories: `multimedia`
- Maintainers: `outloudvi`
- Source Location: `saved.ts`
- Source Module: `() => import('@/routes/spotify/saved.ts')`

## Description
_None_

## Parameters
- `limit`: Track count, 50 by default


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
  - `open.spotify.com/collection/tracks`
- `target`: `/saved`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/spotify/saved/50",
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
  "location": "saved.ts",
  "maintainers": [
    "outloudvi"
  ],
  "module": "() => import('@/routes/spotify/saved.ts')",
  "name": "Personal Saved Tracks",
  "parameters": {
    "limit": "Track count, 50 by default"
  },
  "path": "/saved/:limit?",
  "radar": [
    {
      "source": [
        "open.spotify.com/collection/tracks"
      ],
      "target": "/saved"
    }
  ],
  "url": "open.spotify.com/collection/tracks"
}
```
