# Spotify - Artist Albums

## Coverage
`index-only`

## Route
- Namespace: `spotify`
- Namespace Name: `Spotify`
- Route Path: `/artist/:id`
- Route Name: `Artist Albums`
- Example: `/spotify/artist/6k9TBCxyr4bXwZ8Y21Kwn1`
- URL: `open.spotify.com`
- Language: `en`
- Categories: `multimedia`
- Maintainers: `outloudvi`
- Source Location: `artist.ts`
- Source Module: `() => import('@/routes/spotify/artist.ts')`

## Description
_None_

## Parameters
- `id`: Artist ID


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
  - `open.spotify.com/artist/:id`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/spotify/artist/6k9TBCxyr4bXwZ8Y21Kwn1",
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
  "location": "artist.ts",
  "maintainers": [
    "outloudvi"
  ],
  "module": "() => import('@/routes/spotify/artist.ts')",
  "name": "Artist Albums",
  "parameters": {
    "id": "Artist ID"
  },
  "path": "/artist/:id",
  "radar": [
    {
      "source": [
        "open.spotify.com/artist/:id"
      ]
    }
  ],
  "view": 4
}
```
