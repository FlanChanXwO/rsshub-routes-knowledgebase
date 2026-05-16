# 优酷 - 频道

## Coverage
`index-only`

## Route
- Namespace: `youku`
- Namespace Name: `优酷`
- Route Path: `/youku/channel/:channelId/:embed?`
- Route Name: `频道`
- Example: `/youku/channel/UNTg3MTM3OTcy`
- URL: `i.youku.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `xyqfer, Fatpandac`
- Source Location: `channel.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `channelId`: 频道 id
- `embed`: 默认为开启内嵌视频, 任意值为关闭


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `i.youku.com/i/:id`
- `target`: `/channel/:id`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/youku/channel/UNTg3MTM3OTcy",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "channel.tsx",
  "maintainers": [
    "xyqfer",
    "Fatpandac"
  ],
  "name": "频道",
  "parameters": {
    "channelId": "频道 id",
    "embed": "默认为开启内嵌视频, 任意值为关闭"
  },
  "path": "/channel/:channelId/:embed?",
  "radar": [
    {
      "source": [
        "i.youku.com/i/:id"
      ],
      "target": "/channel/:id"
    }
  ],
  "topFeeds": []
}
```
