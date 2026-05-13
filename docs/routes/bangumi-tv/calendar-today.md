# Bangumi 番组计划 - 放送列表

## Coverage
`index-only`

## Route
- Namespace: `bangumi.tv`
- Namespace Name: `Bangumi 番组计划`
- Route Path: `/calendar/today`
- Route Name: `放送列表`
- Example: `/bangumi.tv/calendar/today`
- URL: `bgm.tv/calendar`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `magic-akari`
- Source Location: `calendar/today.tsx`
- Source Module: `() => import('@/routes/bangumi.tv/calendar/today.tsx')`

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
  - `bgm.tv/calendar`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/bangumi.tv/calendar/today",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "calendar/today.tsx",
  "maintainers": [
    "magic-akari"
  ],
  "module": "() => import('@/routes/bangumi.tv/calendar/today.tsx')",
  "name": "放送列表",
  "parameters": {},
  "path": "/calendar/today",
  "radar": [
    {
      "source": [
        "bgm.tv/calendar"
      ]
    }
  ],
  "url": "bgm.tv/calendar"
}
```
