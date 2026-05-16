# The New York Times - Daily Briefing

## Coverage
`index-only`

## Route
- Namespace: `nytimes`
- Namespace Name: `The New York Times`
- Route Path: `/nytimes/daily_briefing_chinese`
- Route Name: `Daily Briefing`
- Example: `/nytimes/daily_briefing_chinese`
- URL: `nytimes.com/`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `yueyericardo, nczitzk`
- Source Location: `daily-briefing-chinese.tsx`
- Source Module: `_None_`

## Description
URL: <https://www.nytimes.com/zh-hans/series/daily-briefing-chinese>

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
  "description": "URL: <https://www.nytimes.com/zh-hans/series/daily-briefing-chinese>",
  "example": "/nytimes/daily_briefing_chinese",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 56,
  "location": "daily-briefing-chinese.tsx",
  "maintainers": [
    "yueyericardo",
    "nczitzk"
  ],
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
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-05-23T09:51:57.698Z",
      "errorMessage": "[GET] \"https://www.nytimes.com/zh-hans/2023/06/01/world/asia/apartment-feud.html\": 403 Forbidden\n[GET] \"https://www.nytimes.com/zh-hans/series/daily-briefing-chinese\": 403 Forbidden\n",
      "id": "148631391178206293",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://nytimes/daily_briefing_chinese"
    }
  ],
  "url": "nytimes.com/"
}
```
