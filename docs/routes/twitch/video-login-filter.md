# Twitch - Channel Video

## Coverage
`index-only`

## Route
- Namespace: `twitch`
- Namespace Name: `Twitch`
- Route Path: `/video/:login/:filter?`
- Route Name: `Channel Video`
- Example: `/twitch/video/riotgames/highlights`
- URL: `www.twitch.tv`
- Language: `en`
- Categories: `live`
- Maintainers: `hoilc`
- Source Location: `video.ts`
- Source Module: `() => import('@/routes/twitch/video.ts')`

## Description
_None_

## Parameters
- `login`: Twitch username
- `filter`: {"default": "all", "description": "Video type, Default to all", "options": [{"label": "Archive", "value": "archive"}, {"label": "Highlights", "value": "highlights"}, {"label": "All", "value": "all"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.twitch.tv/:login/videos`
- `target`: `/video/:login`

## Raw JSON
```json
{
  "categories": [
    "live"
  ],
  "example": "/twitch/video/riotgames/highlights",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "video.ts",
  "maintainers": [
    "hoilc"
  ],
  "module": "() => import('@/routes/twitch/video.ts')",
  "name": "Channel Video",
  "parameters": {
    "filter": {
      "default": "all",
      "description": "Video type, Default to all",
      "options": [
        {
          "label": "Archive",
          "value": "archive"
        },
        {
          "label": "Highlights",
          "value": "highlights"
        },
        {
          "label": "All",
          "value": "all"
        }
      ]
    },
    "login": "Twitch username"
  },
  "path": "/video/:login/:filter?",
  "radar": [
    {
      "source": [
        "www.twitch.tv/:login/videos"
      ],
      "target": "/video/:login"
    }
  ],
  "view": 3
}
```
