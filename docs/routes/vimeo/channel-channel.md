# Vimeo - Channel

## Coverage
`index-only`

## Route
- Namespace: `vimeo`
- Namespace Name: `Vimeo`
- Route Path: `/channel/:channel`
- Route Name: `Channel`
- Example: `/vimeo/channel/bestoftheyear`
- URL: `vimeo.com`
- Language: `en`
- Categories: `social-media`
- Maintainers: `MisteryMonster`
- Source Location: `channel.ts`
- Source Module: `() => import('@/routes/vimeo/channel.ts')`

## Description
_None_

## Parameters
- `channel`: channel name can get from url like `bestoftheyear` in  [https://vimeo.com/channels/bestoftheyear/videos](https://vimeo.com/channels/bestoftheyear/videos) .


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
  - `vimeo.com/channels/:channel`
  - `vimeo.com/channels/:channel/videos`
  - `vimeo.com/channels/:channel/videos/:sort/:format`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/vimeo/channel/bestoftheyear",
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
    "MisteryMonster"
  ],
  "module": "() => import('@/routes/vimeo/channel.ts')",
  "name": "Channel",
  "parameters": {
    "channel": "channel name can get from url like `bestoftheyear` in  [https://vimeo.com/channels/bestoftheyear/videos](https://vimeo.com/channels/bestoftheyear/videos) ."
  },
  "path": "/channel/:channel",
  "radar": [
    {
      "source": [
        "vimeo.com/channels/:channel",
        "vimeo.com/channels/:channel/videos",
        "vimeo.com/channels/:channel/videos/:sort/:format"
      ]
    }
  ]
}
```
