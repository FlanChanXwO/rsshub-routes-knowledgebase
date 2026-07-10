# UK Parliament - Commonlibrary

## Coverage
`index-only`

## Route
- Namespace: `parliament.uk`
- Namespace Name: `UK Parliament`
- Route Path: `/parliament.uk/commonslibrary/type/:topic?`
- Route Name: `Commonlibrary`
- Example: `/parliament.uk/commonslibrary/type/research-briefing`
- URL: `parliament.uk`
- Language: `_None_`
- Categories: `government`
- Maintainers: `AntiKnot`
- Source Location: `commonslibrary.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `topic`: research by topic, string, example: [research-briefing|data-dashboard]


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/parliament.uk/commonslibrary/type/research-briefing",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "commonslibrary.ts",
  "maintainers": [
    "AntiKnot"
  ],
  "name": "Commonlibrary",
  "parameters": {
    "topic": "research by topic, string, example: [research-briefing|data-dashboard]"
  },
  "path": "/commonslibrary/type/:topic?",
  "topFeeds": [
    {
      "description": "parliament - lordslibrary - research-briefing - Powered by RSSHub",
      "errorAt": "2026-05-19T22:03:29.963Z",
      "errorMessage": "502 Bad Gateway\nFailed to fetch\n",
      "id": "68554046044185600",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://commonslibrary.parliament.uk/type/research-briefing/",
      "title": "parliament - lordslibrary - research-briefing",
      "type": "feed",
      "url": "rsshub://parliament.uk/commonslibrary/type/research-briefing"
    }
  ]
}
```
