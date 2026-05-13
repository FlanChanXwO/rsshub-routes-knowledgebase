# SegmentFault - 频道

## Coverage
`index-only`

## Route
- Namespace: `segmentfault`
- Namespace Name: `SegmentFault`
- Route Path: `/channel/:name`
- Route Name: `频道`
- Example: `/segmentfault/channel/frontend`
- URL: `segmentfault.com`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `LogicJake, Fatpandac`
- Source Location: `channel.ts`
- Source Module: `() => import('@/routes/segmentfault/channel.ts')`

## Description
_None_

## Parameters
- `name`: 频道名称，在频道 URL 可以找到


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
  - `segmentfault.com/channel/:name`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/segmentfault/channel/frontend",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "channel.ts",
  "maintainers": [
    "LogicJake",
    "Fatpandac"
  ],
  "module": "() => import('@/routes/segmentfault/channel.ts')",
  "name": "频道",
  "parameters": {
    "name": "频道名称，在频道 URL 可以找到"
  },
  "path": "/channel/:name",
  "radar": [
    {
      "source": [
        "segmentfault.com/channel/:name"
      ]
    }
  ]
}
```
