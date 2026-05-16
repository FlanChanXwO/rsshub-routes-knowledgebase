# BFL AI - Announcements

## Coverage
`index-only`

## Route
- Namespace: `bfl`
- Namespace Name: `BFL AI`
- Route Path: `/bfl/announcements`
- Route Name: `Announcements`
- Example: `/bfl/announcements`
- URL: `bfl.ai/announcements`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `thirteenkai`
- Source Location: `announcements.ts`
- Source Module: `_None_`

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
  "heat": 11,
  "location": "announcements.ts",
  "maintainers": [
    "thirteenkai"
  ],
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
  "topFeeds": [
    {
      "description": "Amazing AI models from the Black Forest. - Powered by RSSHub",
      "errorAt": "2025-08-14T22:53:13.018Z",
      "errorMessage": "404 Not Found\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "153814816828039168",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bfl.ai/announcements",
      "title": "Black Forest Labs - Frontier AI Lab",
      "type": "feed",
      "url": "rsshub://bfl/announcements"
    }
  ],
  "url": "bfl.ai/announcements"
}
```
