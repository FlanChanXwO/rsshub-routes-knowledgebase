# BFL AI - Announcements

## Coverage
`index-only`

## Route
- Namespace: `bfl`
- Namespace Name: `BFL AI`
- Route Path: `/announcements`
- Route Name: `Announcements`
- Example: `/bfl/announcements`
- URL: `bfl.ai/announcements`
- Language: `en`
- Categories: `multimedia`
- Maintainers: `thirteenkai`
- Source Location: `announcements.ts`
- Source Module: `() => import('@/routes/bfl/announcements.ts')`

## Description
Fetches the latest announcements from Black Forest Labs (bfl.ai). Provides full article content by default with caching.

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
  - `bfl.ai/announcements`
- `target`: `/announcements`
- `title`: `Announcements`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "Fetches the latest announcements from Black Forest Labs (bfl.ai). Provides full article content by default with caching.",
  "example": "/bfl/announcements",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "announcements.ts",
  "maintainers": [
    "thirteenkai"
  ],
  "module": "() => import('@/routes/bfl/announcements.ts')",
  "name": "Announcements",
  "parameters": {},
  "path": "/announcements",
  "radar": [
    {
      "source": [
        "bfl.ai/announcements"
      ],
      "target": "/announcements",
      "title": "Announcements"
    }
  ],
  "url": "bfl.ai/announcements"
}
```
