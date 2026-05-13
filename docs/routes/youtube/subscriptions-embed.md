# YouTube - Subscriptions

## Coverage
`index-only`

## Route
- Namespace: `youtube`
- Namespace Name: `YouTube`
- Route Path: `/subscriptions/:embed?`
- Route Name: `Subscriptions`
- Example: `/youtube/subscriptions`
- URL: `www.youtube.com/feed/subscriptions`
- Language: `en`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `subscriptions.ts`
- Source Module: `() => import('@/routes/youtube/subscriptions.ts')`

## Description
_None_

## Parameters
- `embed`: Default to embed the video, set to any value to disable embedding


## Features
- `requireConfig`: [{"description": "", "name": "YOUTUBE_KEY"}, {"description": "", "name": "YOUTUBE_CLIENT_ID"}, {"description": "", "name": "YOUTUBE_CLIENT_SECRET"}, {"description": "", "name": "YOUTUBE_REFRESH_TOKEN"}]

## Radar
### Rule 1
- `source`:
  - `www.youtube.com/feed/subscriptions`
  - `www.youtube.com/feed/channels`
- `target`: `/subscriptions`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/youtube/subscriptions",
  "features": {
    "requireConfig": [
      {
        "description": "",
        "name": "YOUTUBE_KEY"
      },
      {
        "description": "",
        "name": "YOUTUBE_CLIENT_ID"
      },
      {
        "description": "",
        "name": "YOUTUBE_CLIENT_SECRET"
      },
      {
        "description": "",
        "name": "YOUTUBE_REFRESH_TOKEN"
      }
    ]
  },
  "location": "subscriptions.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/youtube/subscriptions.ts')",
  "name": "Subscriptions",
  "parameters": {
    "embed": "Default to embed the video, set to any value to disable embedding"
  },
  "path": "/subscriptions/:embed?",
  "radar": [
    {
      "source": [
        "www.youtube.com/feed/subscriptions",
        "www.youtube.com/feed/channels"
      ],
      "target": "/subscriptions"
    }
  ],
  "url": "www.youtube.com/feed/subscriptions"
}
```
