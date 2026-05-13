# Ganjing World - Shorts in a channel

## Coverage
`index-only`

## Route
- Namespace: `ganjingworld`
- Namespace Name: `Ganjing World`
- Route Path: `/channel/shorts/:id`
- Route Name: `Shorts in a channel`
- Example: `/ganjingworld/channel/shorts/1fq5chh3ajo67UNu14uAvfzOp1a80c`
- URL: `www.ganjingworld.com`
- Language: `en`
- Categories: `social-media`
- Maintainers: `yixiangli2001`
- Source Location: `channel/shorts.ts`
- Source Module: `() => import('@/routes/ganjingworld/channel/shorts.ts')`

## Description
_None_

## Parameters
- `id`: Channel ID, can be found in channel url


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
  - `ganjingworld.com`
- `target`: `/channel/shorts/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/ganjingworld/channel/shorts/1fq5chh3ajo67UNu14uAvfzOp1a80c",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "channel/shorts.ts",
  "maintainers": [
    "yixiangli2001"
  ],
  "module": "() => import('@/routes/ganjingworld/channel/shorts.ts')",
  "name": "Shorts in a channel",
  "parameters": {
    "id": "Channel ID, can be found in channel url"
  },
  "path": "/channel/shorts/:id",
  "radar": [
    {
      "source": [
        "ganjingworld.com"
      ],
      "target": "/channel/shorts/:id"
    }
  ],
  "url": "www.ganjingworld.com"
}
```
