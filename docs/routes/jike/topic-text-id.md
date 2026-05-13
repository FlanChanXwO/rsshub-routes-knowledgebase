# 即刻 - 圈子 - 纯文字

## Coverage
`index-only`

## Route
- Namespace: `jike`
- Namespace Name: `即刻`
- Route Path: `/topic/text/:id`
- Route Name: `圈子 - 纯文字`
- Example: `/jike/topic/text/553870e8e4b0cafb0a1bef68`
- URL: `m.okjike.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `HenryQW`
- Source Location: `topic-text.ts`
- Source Module: `() => import('@/routes/jike/topic-text.ts')`

## Description
_None_

## Parameters
- `id`: 圈子 id, 可在即刻 web 端圈子页或 APP 分享出来的圈子页 URL 中找到


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
  - `web.okjike.com/topic/:id`
- `target`: `/topic/text/:id`
### Rule 2
- `source`:
  - `m.okjike.com/topics/:id`
- `target`: `/topic/text/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/jike/topic/text/553870e8e4b0cafb0a1bef68",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "topic-text.ts",
  "maintainers": [
    "HenryQW"
  ],
  "module": "() => import('@/routes/jike/topic-text.ts')",
  "name": "圈子 - 纯文字",
  "parameters": {
    "id": "圈子 id, 可在即刻 web 端圈子页或 APP 分享出来的圈子页 URL 中找到"
  },
  "path": "/topic/text/:id",
  "radar": [
    {
      "source": [
        "web.okjike.com/topic/:id"
      ],
      "target": "/topic/text/:id"
    },
    {
      "source": [
        "m.okjike.com/topics/:id"
      ],
      "target": "/topic/text/:id"
    }
  ]
}
```
