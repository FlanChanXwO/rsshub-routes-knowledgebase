# YouTube - Channel with user handle

## Coverage
`index-only`

## Route
- Namespace: `youtube`
- Namespace Name: `YouTube`
- Route Path: `/user/:username/:routeParams?`
- Route Name: `Channel with user handle`
- Example: `/youtube/user/@JFlaMusic`
- URL: `youtube.com`
- Language: `en`
- Categories: `social-media`
- Maintainers: `DIYgod, pseudoyu`
- Source Location: `user.ts`
- Source Module: `() => import('@/routes/youtube/user.ts')`

## Description
::: tip Parameter
| Name       | Description                                                                         | Default |
| ---------- | ----------------------------------------------------------------------------------- | ------- |
| embed      | Whether to embed the video, fill in any value to disable embedding                  | embed   |
| filterShorts | Whether to filter out shorts from the feed, fill in any falsy value to show shorts | true    |
:::

## Parameters
- `username`: YouTuber handle with @
- `routeParams`: Extra parameters, see the table below


## Features
- `requireConfig`: [{"description": " YouTube API Key, support multiple keys, split them with `,`, [API Key application](https://console.developers.google.com/)", "name": "YOUTUBE_KEY", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.youtube.com/user/:username`
  - `www.youtube.com/:username`
  - `www.youtube.com/:username/videos`
- `target`: `/user/:username`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "::: tip Parameter\n| Name       | Description                                                                         | Default |\n| ---------- | ----------------------------------------------------------------------------------- | ------- |\n| embed      | Whether to embed the video, fill in any value to disable embedding                  | embed   |\n| filterShorts | Whether to filter out shorts from the feed, fill in any falsy value to show shorts | true    |\n:::",
  "example": "/youtube/user/@JFlaMusic",
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
  "location": "user.ts",
  "maintainers": [
    "DIYgod",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/youtube/user.ts')",
  "name": "Channel with user handle",
  "parameters": {
    "routeParams": "Extra parameters, see the table below",
    "username": "YouTuber handle with @"
  },
  "path": "/user/:username/:routeParams?",
  "radar": [
    {
      "source": [
        "www.youtube.com/user/:username",
        "www.youtube.com/:username",
        "www.youtube.com/:username/videos"
      ],
      "target": "/user/:username"
    }
  ],
  "view": 3
}
```
