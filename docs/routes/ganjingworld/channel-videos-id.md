# Ganjing World - Videos in a channel

## Coverage
`index-only`

## Route
- Namespace: `ganjingworld`
- Namespace Name: `Ganjing World`
- Route Path: `/channel/videos/:id`
- Route Name: `Videos in a channel`
- Example: `/ganjingworld/channel/videos/1eiqjdnq7go1OPYtIbLDVMpM61ok0c`
- URL: `www.ganjingworld.com`
- Language: `en`
- Categories: `social-media`
- Maintainers: `yixiangli2001`
- Source Location: `channel/videos.ts`
- Source Module: `() => import('@/routes/ganjingworld/channel/videos.ts')`

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
- `target`: `/channel/videos/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/ganjingworld/channel/videos/1eiqjdnq7go1OPYtIbLDVMpM61ok0c",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "channel/videos.ts",
  "maintainers": [
    "yixiangli2001"
  ],
  "module": "() => import('@/routes/ganjingworld/channel/videos.ts')",
  "name": "Videos in a channel",
  "parameters": {
    "id": "Channel ID, can be found in channel url"
  },
  "path": "/channel/videos/:id",
  "radar": [
    {
      "source": [
        "ganjingworld.com"
      ],
      "target": "/channel/videos/:id"
    }
  ],
  "url": "www.ganjingworld.com"
}
```
