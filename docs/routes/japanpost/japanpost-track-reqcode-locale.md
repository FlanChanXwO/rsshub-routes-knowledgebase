# Japanpost - Track & Trace Service

## Coverage
`index-only`

## Route
- Namespace: `japanpost`
- Namespace Name: `Japanpost`
- Route Path: `/japanpost/track/:reqCode/:locale?`
- Route Name: `Track & Trace Service`
- Example: `/japanpost/track/EJ123456789JP/en`
- URL: `trackings.post.japanpost.jp/services/srv/search/`
- Language: `_None_`
- Categories: `other`
- Maintainers: `tuzi3040`
- Source Location: `router.ts`
- Source Module: `_None_`

## Description
| Japanese | English |
| -------- | ------- |
| ja       | en      |

## Parameters
- `reqCode`: Package Number
- `locale`: Language, default to japanese `ja`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "| Japanese | English |\n| -------- | ------- |\n| ja       | en      |",
  "example": "/japanpost/track/EJ123456789JP/en",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "router.ts",
  "maintainers": [
    "tuzi3040"
  ],
  "name": "Track & Trace Service",
  "parameters": {
    "locale": "Language, default to japanese `ja`",
    "reqCode": "Package Number"
  },
  "path": "/track/:reqCode/:locale?",
  "topFeeds": [],
  "url": "trackings.post.japanpost.jp/services/srv/search/",
  "zh": {
    "description": "| 日语 | 英语 |\n| ---- | ---- |\n| ja   | en   |",
    "name": "邮件追踪查询"
  }
}
```
