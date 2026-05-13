# YouTube - Playlist

## Coverage
`index-only`

## Route
- Namespace: `youtube`
- Namespace Name: `YouTube`
- Route Path: `/playlist/:id/:embed?`
- Route Name: `Playlist`
- Example: `/youtube/playlist/PLqQ1RwlxOgeLTJ1f3fNMSwhjVgaWKo_9Z`
- URL: `youtube.com`
- Language: `en`
- Categories: `social-media`
- Maintainers: `HenryQW`
- Source Location: `playlist.ts`
- Source Module: `() => import('@/routes/youtube/playlist.ts')`

## Description
_None_

## Parameters
- `id`: YouTube playlist id
- `embed`: Default to embed the video, set to any value to disable embedding


## Features
- `requireConfig`: [{"description": " YouTube API Key, support multiple keys, split them with `,`, [API Key application](https://console.developers.google.com/)", "name": "YOUTUBE_KEY", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/youtube/playlist/PLqQ1RwlxOgeLTJ1f3fNMSwhjVgaWKo_9Z",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": " YouTube API Key, support multiple keys, split them with `,`, [API Key application](https://console.developers.google.com/)",
        "name": "YOUTUBE_KEY",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "playlist.ts",
  "maintainers": [
    "HenryQW"
  ],
  "module": "() => import('@/routes/youtube/playlist.ts')",
  "name": "Playlist",
  "parameters": {
    "embed": "Default to embed the video, set to any value to disable embedding",
    "id": "YouTube playlist id"
  },
  "path": "/playlist/:id/:embed?",
  "view": 3
}
```
