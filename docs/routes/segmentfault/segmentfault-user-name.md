# SegmentFault - 用户

## Coverage
`index-only`

## Route
- Namespace: `segmentfault`
- Namespace Name: `SegmentFault`
- Route Path: `/segmentfault/user/:name`
- Route Name: `用户`
- Example: `/segmentfault/user/minnanitkong`
- URL: `segmentfault.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `leyuuu, Fatpandac`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `name`: 用户 Id，用户详情页 URL 可以找到


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
  - `segmentfault.com/u/:name`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/segmentfault/user/minnanitkong",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "user.ts",
  "maintainers": [
    "leyuuu",
    "Fatpandac"
  ],
  "name": "用户",
  "parameters": {
    "name": "用户 Id，用户详情页 URL 可以找到"
  },
  "path": "/user/:name",
  "radar": [
    {
      "source": [
        "segmentfault.com/u/:name"
      ]
    }
  ],
  "topFeeds": []
}
```
