# 風傳媒 - 频道

## Coverage
`index-only`

## Route
- Namespace: `storm`
- Namespace Name: `風傳媒`
- Route Path: `/channel/:id?`
- Route Name: `频道`
- Example: `/storm/channel/2`
- URL: `storm.mg`
- Language: `zh-TW`
- Categories: `new-media`
- Maintainers: `dzx-dzx`
- Source Location: `channel.ts`
- Source Module: `() => import('@/routes/storm/channel.ts')`

## Description
_None_

## Parameters
- `id`: ID，可在 URL 中找到


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
  - `storm.mg/channel/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/storm/channel/2",
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
    "dzx-dzx"
  ],
  "module": "() => import('@/routes/storm/channel.ts')",
  "name": "频道",
  "parameters": {
    "id": "ID，可在 URL 中找到"
  },
  "path": "/channel/:id?",
  "radar": [
    {
      "source": [
        "storm.mg/channel/:id"
      ]
    }
  ]
}
```
