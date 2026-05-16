# Niconico - User Videos

## Coverage
`index-only`

## Route
- Namespace: `nicovideo`
- Namespace Name: `Niconico`
- Route Path: `/nicovideo/user/:id/video/:embed?`
- Route Name: `User Videos`
- Example: `/nicovideo/user/16690815/video`
- URL: `www.nicovideo.jp`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `TonyRL`
- Source Location: `video.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: User ID
- `embed`: Default to embed the video, set to any value to disable embedding


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.nicovideo.jp/user/:id`
  - `www.nicovideo.jp/user/:id/video`
- `target`: `/user/:id/video`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/nicovideo/user/16690815/video",
  "heat": 47,
  "location": "video.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "User Videos",
  "parameters": {
    "embed": "Default to embed the video, set to any value to disable embedding",
    "id": "User ID"
  },
  "path": "/user/:id/video/:embed?",
  "radar": [
    {
      "source": [
        "www.nicovideo.jp/user/:id",
        "www.nicovideo.jp/user/:id/video"
      ],
      "target": "/user/:id/video"
    }
  ],
  "topFeeds": [
    {
      "description": "ピノキオピー - ニコニコ - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "67834533653006336",
      "image": "https://secure-dcdn.cdn.nimg.jp/nicoaccount/usericon/86/865591.jpg?1692257539",
      "ownerUserId": null,
      "siteUrl": "https://www.nicovideo.jp/user/865591/video",
      "title": "ピノキオピー - ニコニコ",
      "type": "feed",
      "url": "rsshub://nicovideo/user/865591/video"
    },
    {
      "description": "十六夜カズヤP - ニコニコ - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "173365214757950464",
      "image": "https://secure-dcdn.cdn.nimg.jp/nicoaccount/usericon/321/3219731.jpg?1422604697",
      "ownerUserId": null,
      "siteUrl": "https://www.nicovideo.jp/user/3219731/video",
      "title": "十六夜カズヤP - ニコニコ",
      "type": "feed",
      "url": "rsshub://nicovideo/user/3219731/video"
    }
  ]
}
```
