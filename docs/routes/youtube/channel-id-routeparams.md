# YouTube - Channel with id

## Coverage
`index-only`

## Route
- Namespace: `youtube`
- Namespace Name: `YouTube`
- Route Path: `/channel/:id/:routeParams?`
- Route Name: `Channel with id`
- Example: `/youtube/channel/UCDwDMPOZfxVV0x_dz0eQ8KQ`
- URL: `youtube.com`
- Language: `en`
- Categories: `social-media`
- Maintainers: `DIYgod, pseudoyu`
- Source Location: `channel.ts`
- Source Module: `() => import('@/routes/youtube/channel.ts')`

## Description
::: tip Parameter
| Name       | Description                                                                         | Default |
| ---------- | ----------------------------------------------------------------------------------- | ------- |
| embed      | Whether to embed the video, fill in any value to disable embedding                  | embed   |
| filterShorts | Whether to filter out shorts from the feed, fill in any falsy value to show shorts | true    |
:::

::: tip
YouTube provides official RSS feeds for channels, for instance [https://www.youtube.com/feeds/videos.xml?channel_id=UCDwDMPOZfxVV0x_dz0eQ8KQ](https://www.youtube.com/feeds/videos.xml?channel_id=UCDwDMPOZfxVV0x_dz0eQ8KQ).
:::

## Parameters
- `id`: YouTube channel id
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
  - `www.youtube.com/channel/:id`
- `target`: `/channel/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "::: tip Parameter\n| Name       | Description                                                                         | Default |\n| ---------- | ----------------------------------------------------------------------------------- | ------- |\n| embed      | Whether to embed the video, fill in any value to disable embedding                  | embed   |\n| filterShorts | Whether to filter out shorts from the feed, fill in any falsy value to show shorts | true    |\n:::\n\n::: tip\nYouTube provides official RSS feeds for channels, for instance [https://www.youtube.com/feeds/videos.xml?channel_id=UCDwDMPOZfxVV0x_dz0eQ8KQ](https://www.youtube.com/feeds/videos.xml?channel_id=UCDwDMPOZfxVV0x_dz0eQ8KQ).\n:::",
  "example": "/youtube/channel/UCDwDMPOZfxVV0x_dz0eQ8KQ",
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
  "location": "channel.ts",
  "maintainers": [
    "DIYgod",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/youtube/channel.ts')",
  "name": "Channel with id",
  "parameters": {
    "id": "YouTube channel id",
    "routeParams": "Extra parameters, see the table below"
  },
  "path": "/channel/:id/:routeParams?",
  "radar": [
    {
      "source": [
        "www.youtube.com/channel/:id"
      ],
      "target": "/channel/:id"
    }
  ]
}
```
