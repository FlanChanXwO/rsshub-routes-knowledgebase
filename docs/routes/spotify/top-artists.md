# Spotify - Personal Top Artists

## Coverage
`index-only`

## Route
- Namespace: `spotify`
- Namespace Name: `Spotify`
- Route Path: `/top/artists`
- Route Name: `Personal Top Artists`
- Example: `/spotify/top/artists`
- URL: `open.spotify.com/`
- Language: `en`
- Categories: `multimedia`
- Maintainers: `outloudvi`
- Source Location: `artists-top.ts`
- Source Module: `() => import('@/routes/spotify/artists-top.ts')`

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
  "example": "/spotify/top/artists",
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
  "location": "artists-top.ts",
  "maintainers": [
    "outloudvi"
  ],
  "module": "() => import('@/routes/spotify/artists-top.ts')",
  "name": "Personal Top Artists",
  "parameters": {},
  "path": "/top/artists",
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
