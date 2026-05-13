# Vimeo - Channel

## Coverage
`index-only`

## Route
- Namespace: `vimeo`
- Namespace Name: `Vimeo`
- Route Path: `/vimeo/channel/:channel`
- Route Name: `Channel`
- Example: `/vimeo/channel/bestoftheyear`
- URL: `vimeo.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `MisteryMonster`
- Source Location: `channel.ts`
- Source Module: `_None_`

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
  "heat": 0,
  "location": "channel.ts",
  "maintainers": [
    "MisteryMonster"
  ],
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
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
