# LuMa - Events

## Coverage
`index-only`

## Route
- Namespace: `luma`
- Namespace Name: `LuMa`
- Route Path: `/:url`
- Route Name: `Events`
- Example: `/luma/yieldnest`
- URL: `lu.ma`
- Language: `zh-CN`
- Categories: `other`
- Maintainers: `cxheng315`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/luma/index.ts')`

## Description
_None_

## Parameters
- `url`: LuMa URL


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
  - `lu.ma/:url`
- `target`: `/:url`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/luma/yieldnest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "cxheng315"
  ],
  "module": "() => import('@/routes/luma/index.ts')",
  "name": "Events",
  "parameters": {
    "url": "LuMa URL"
  },
  "path": "/:url",
  "radar": [
    {
      "source": [
        "lu.ma/:url"
      ],
      "target": "/:url"
    }
  ],
  "url": "lu.ma"
}
```
