# The New York Times - Daily Briefing

## Coverage
`index-only`

## Route
- Namespace: `nytimes`
- Namespace Name: `The New York Times`
- Route Path: `/daily_briefing_chinese`
- Route Name: `Daily Briefing`
- Example: `/nytimes/daily_briefing_chinese`
- URL: `nytimes.com/`
- Language: `en`
- Categories: `traditional-media`
- Maintainers: `yueyericardo, nczitzk`
- Source Location: `daily-briefing-chinese.tsx`
- Source Module: `() => import('@/routes/nytimes/daily-briefing-chinese.tsx')`

## Description
URL: [https://www.nytimes.com/zh-hans/series/daily-briefing-chinese](https://www.nytimes.com/zh-hans/series/daily-briefing-chinese)

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
  - `nytimes.com/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "URL: [https://www.nytimes.com/zh-hans/series/daily-briefing-chinese](https://www.nytimes.com/zh-hans/series/daily-briefing-chinese)",
  "example": "/nytimes/daily_briefing_chinese",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "daily-briefing-chinese.tsx",
  "maintainers": [
    "yueyericardo",
    "nczitzk"
  ],
  "module": "() => import('@/routes/nytimes/daily-briefing-chinese.tsx')",
  "name": "Daily Briefing",
  "parameters": {},
  "path": "/daily_briefing_chinese",
  "radar": [
    {
      "source": [
        "nytimes.com/"
      ],
      "target": ""
    }
  ],
  "url": "nytimes.com/"
}
```
