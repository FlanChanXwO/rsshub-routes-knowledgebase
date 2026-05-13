# 电獭少女 - 精选主题

## Coverage
`index-only`

## Route
- Namespace: `agirls`
- Namespace Name: `电獭少女`
- Route Path: `/topic/:topic`
- Route Name: `精选主题`
- Example: `/agirls/topic/AppleWatch`
- URL: `agirls.aotter.net`
- Language: `zh-TW`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `topic.ts`
- Source Module: `() => import('@/routes/agirls/topic.ts')`

## Description
_None_

## Parameters
- `topic`: 精选主题，可通过下方精选主题列表获得


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
  - `agirls.aotter.net/topic/:topic`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/agirls/topic/AppleWatch",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "topic.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/agirls/topic.ts')",
  "name": "精选主题",
  "parameters": {
    "topic": "精选主题，可通过下方精选主题列表获得"
  },
  "path": "/topic/:topic",
  "radar": [
    {
      "source": [
        "agirls.aotter.net/topic/:topic"
      ]
    }
  ]
}
```
