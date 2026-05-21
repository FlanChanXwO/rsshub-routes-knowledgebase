# Quanta Magazine - Archive

## Coverage
`index-only`

## Route
- Namespace: `quantamagazine`
- Namespace Name: `Quanta Magazine`
- Route Path: `/quantamagazine/archive`
- Route Name: `Archive`
- Example: `/quantamagazine/archive`
- URL: `quantamagazine.org`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `emdoe`
- Source Location: `archive.ts`
- Source Module: `_None_`

## Description
Get the latest articles from Quanta Magazine.

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `quantamagazine.org`
- `target`: `/archive`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "Get the latest articles from Quanta Magazine.",
  "example": "/quantamagazine/archive",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 3,
  "location": "archive.ts",
  "maintainers": [
    "emdoe"
  ],
  "name": "Archive",
  "parameters": {},
  "path": "/archive",
  "radar": [
    {
      "source": [
        "quantamagazine.org"
      ],
      "target": "/archive"
    }
  ],
  "topFeeds": [
    {
      "description": "Quanta Magazine - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "145148341029475363",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.quantamagazine.org/",
      "title": "Quanta Magazine",
      "type": "feed",
      "url": "rsshub://quantamagazine/archive"
    }
  ],
  "url": "quantamagazine.org"
}
```
