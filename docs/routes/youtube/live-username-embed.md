# YouTube - Live

## Coverage
`index-only`

## Route
- Namespace: `youtube`
- Namespace Name: `YouTube`
- Route Path: `/live/:username/:embed?`
- Route Name: `Live`
- Example: `/youtube/live/@GawrGura`
- URL: `youtube.com`
- Language: `en`
- Categories: `live`
- Maintainers: `sussurr127`
- Source Location: `live.ts`
- Source Module: `() => import('@/routes/youtube/live.ts')`

## Description
_None_

## Parameters
- `username`: YouTuber id
- `embed`: Default to embed the video, set to any value to disable embedding


## Features
- `requireConfig`: [{"description": "YouTube API Key (enable YouTube Data API v3), support multiple keys, split them with `,`, [API Key application](https://console.developers.google.com/), [YouTube Data API v3](https://console.cloud.google.com/apis/library/youtube.googleapis.com)", "name": "YOUTUBE_KEY"}]
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
    "live"
  ],
  "example": "/youtube/live/@GawrGura",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "YouTube API Key (enable YouTube Data API v3), support multiple keys, split them with `,`, [API Key application](https://console.developers.google.com/), [YouTube Data API v3](https://console.cloud.google.com/apis/library/youtube.googleapis.com)",
        "name": "YOUTUBE_KEY"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "live.ts",
  "maintainers": [
    "sussurr127"
  ],
  "module": "() => import('@/routes/youtube/live.ts')",
  "name": "Live",
  "parameters": {
    "embed": "Default to embed the video, set to any value to disable embedding",
    "username": "YouTuber id"
  },
  "path": "/live/:username/:embed?"
}
```
