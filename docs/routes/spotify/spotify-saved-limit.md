# Spotify - Personal Saved Tracks

## Coverage
`index-only`

## Route
- Namespace: `spotify`
- Namespace Name: `Spotify`
- Route Path: `/spotify/saved/:limit?`
- Route Name: `Personal Saved Tracks`
- Example: `/spotify/saved/50`
- URL: `open.spotify.com/collection/tracks`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `outloudvi`
- Source Location: `saved.ts`
- Source Module: `_None_`

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
  "heat": 3,
  "location": "saved.ts",
  "maintainers": [
    "outloudvi"
  ],
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
  "topFeeds": [
    {
      "description": "Latest 50 saved tracks on Spotify. - Powered by RSSHub",
      "errorAt": "2026-03-11T18:39:35.574Z",
      "errorMessage": "[GET] \"https://api.spotify.com/v1/me/tracks?limit=50\": 403 Forbidden\n",
      "id": "160848855950287872",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://open.spotify.com/collection/tracks",
      "title": "Spotify: My Saved Tracks",
      "type": "feed",
      "url": "rsshub://spotify/saved"
    }
  ],
  "url": "open.spotify.com/collection/tracks"
}
```
