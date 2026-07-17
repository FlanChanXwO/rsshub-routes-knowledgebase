# Futubull 富途牛牛 - 视频

## Coverage
`index-only`

## Route
- Namespace: `futunn`
- Namespace Name: `Futubull 富途牛牛`
- Route Path: `/futunn/video`
- Route Name: `视频`
- Example: `/futunn/video`
- URL: `news.futunn.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `kennyfong19931`
- Source Location: `video.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `news.futunn.com/main/video-list`
  - `news.futunn.com/:lang/main/video-list`
- `target`: `/video`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/futunn/video",
  "features": {
    "supportRadar": true
  },
  "heat": 0,
  "location": "video.ts",
  "maintainers": [
    "kennyfong19931"
  ],
  "name": "视频",
  "path": "/video",
  "radar": [
    {
      "source": [
        "news.futunn.com/main/video-list",
        "news.futunn.com/:lang/main/video-list"
      ],
      "target": "/video"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
