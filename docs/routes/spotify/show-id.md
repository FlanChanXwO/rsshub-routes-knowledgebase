# Spotify - Show/Podcasts

## Coverage
`index-only`

## Route
- Namespace: `spotify`
- Namespace Name: `Spotify`
- Route Path: `/show/:id`
- Route Name: `Show/Podcasts`
- Example: `/spotify/show/5CfCWKI5pZ28U0uOzXkDHe`
- URL: `open.spotify.com`
- Language: `en`
- Categories: `multimedia`
- Maintainers: `caiohsramos, pseudoyu`
- Source Location: `show.ts`
- Source Module: `() => import('@/routes/spotify/show.ts')`

## Description
_None_

## Parameters
- `id`: Show ID


## Features
- `requireConfig`: [{"description": "", "name": "SPOTIFY_CLIENT_ID"}, {"description": "", "name": "SPOTIFY_CLIENT_SECRET"}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `open.spotify.com/show/:id`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/spotify/show/5CfCWKI5pZ28U0uOzXkDHe",
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
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "show.ts",
  "maintainers": [
    "caiohsramos",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/spotify/show.ts')",
  "name": "Show/Podcasts",
  "parameters": {
    "id": "Show ID"
  },
  "path": "/show/:id",
  "radar": [
    {
      "source": [
        "open.spotify.com/show/:id"
      ]
    }
  ],
  "view": 4
}
```
