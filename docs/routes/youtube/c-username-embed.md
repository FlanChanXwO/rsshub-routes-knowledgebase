# YouTube - Custom URL

## Coverage
`index-only`

## Route
- Namespace: `youtube`
- Namespace Name: `YouTube`
- Route Path: `/c/:username/:embed?`
- Route Name: `Custom URL`
- Example: `/youtube/c/YouTubeCreators`
- URL: `youtube.com`
- Language: `en`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `custom.ts`
- Source Module: `() => import('@/routes/youtube/custom.ts')`

## Description
_None_

## Parameters
- `username`: YouTube custom URL
- `embed`: Default to embed the video, set to any value to disable embedding


## Features
- `requireConfig`: [{"description": " YouTube API Key, support multiple keys, split them with `,`, [API Key application](https://console.developers.google.com/)", "name": "YOUTUBE_KEY"}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.youtube.com/c/:id`
- `target`: `/c/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/youtube/c/YouTubeCreators",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": " YouTube API Key, support multiple keys, split them with `,`, [API Key application](https://console.developers.google.com/)",
        "name": "YOUTUBE_KEY"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "custom.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/youtube/custom.ts')",
  "name": "Custom URL",
  "parameters": {
    "embed": "Default to embed the video, set to any value to disable embedding",
    "username": "YouTube custom URL"
  },
  "path": "/c/:username/:embed?",
  "radar": [
    {
      "source": [
        "www.youtube.com/c/:id"
      ],
      "target": "/c/:id"
    }
  ]
}
```
