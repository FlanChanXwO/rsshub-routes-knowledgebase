# 华尔街见闻 - 财经日历

## Coverage
`index-only`

## Route
- Namespace: `wallstreetcn`
- Namespace Name: `华尔街见闻`
- Route Path: `/calendar/:section?`
- Route Name: `财经日历`
- Example: `/wallstreetcn/calendar`
- URL: `wallstreetcn.com/calendar`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `TonyRL`
- Source Location: `calendar.ts`
- Source Module: `() => import('@/routes/wallstreetcn/calendar.ts')`

## Description
_None_

## Parameters
- `section`: `macrodatas` 或 `report`，默认为 `macrodatas`


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
  - `wallstreetcn.com/calendar`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/wallstreetcn/calendar",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "calendar.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/wallstreetcn/calendar.ts')",
  "name": "财经日历",
  "parameters": {
    "section": "`macrodatas` 或 `report`，默认为 `macrodatas`"
  },
  "path": "/calendar/:section?",
  "radar": [
    {
      "source": [
        "wallstreetcn.com/calendar"
      ]
    }
  ],
  "url": "wallstreetcn.com/calendar"
}
```
