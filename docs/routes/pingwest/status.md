# 品玩 - 实时要闻

## Coverage
`index-only`

## Route
- Namespace: `pingwest`
- Namespace Name: `品玩`
- Route Path: `/status`
- Route Name: `实时要闻`
- Example: `/pingwest/status`
- URL: `pingwest.com/status`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `sanmmm`
- Source Location: `status.ts`
- Source Module: `() => import('@/routes/pingwest/status.ts')`

## Description
_None_

## Parameters
_None_


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
  - `pingwest.com/status`
  - `pingwest.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/pingwest/status",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "status.ts",
  "maintainers": [
    "sanmmm"
  ],
  "module": "() => import('@/routes/pingwest/status.ts')",
  "name": "实时要闻",
  "parameters": {},
  "path": "/status",
  "radar": [
    {
      "source": [
        "pingwest.com/status",
        "pingwest.com/"
      ]
    }
  ],
  "url": "pingwest.com/status"
}
```
