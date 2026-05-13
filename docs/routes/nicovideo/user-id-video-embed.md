# Niconico - User Videos

## Coverage
`index-only`

## Route
- Namespace: `nicovideo`
- Namespace Name: `Niconico`
- Route Path: `/user/:id/video/:embed?`
- Route Name: `User Videos`
- Example: `/nicovideo/user/16690815/video`
- URL: `www.nicovideo.jp`
- Language: `ja`
- Categories: `multimedia`
- Maintainers: `TonyRL`
- Source Location: `video.ts`
- Source Module: `() => import('@/routes/nicovideo/video.ts')`

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
  "example": "/nicovideo/user/16690815/video",
  "location": "video.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/nicovideo/video.ts')",
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
  ]
}
```
