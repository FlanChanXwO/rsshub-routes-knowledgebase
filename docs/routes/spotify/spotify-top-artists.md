# Spotify - Personal Top Artists

## Coverage
`index-only`

## Route
- Namespace: `spotify`
- Namespace Name: `Spotify`
- Route Path: `/spotify/top/artists`
- Route Name: `Personal Top Artists`
- Example: `/spotify/top/artists`
- URL: `open.spotify.com/`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `outloudvi`
- Source Location: `artists-top.ts`
- Source Module: `_None_`

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
  "heat": 16,
  "location": "artists-top.ts",
  "maintainers": [
    "outloudvi"
  ],
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
  "topFeeds": [
    {
      "description": "Spotify: My Top Artists - Powered by RSSHub",
      "errorAt": "2026-03-12T05:56:28.822Z",
      "errorMessage": "[GET] \"https://api.spotify.com/v1/me/top/artists\": 403 Forbidden\n",
      "id": "60272158594622464",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "Spotify: My Top Artists",
      "type": "feed",
      "url": "rsshub://spotify/top/artists"
    }
  ],
  "url": "open.spotify.com/"
}
```
