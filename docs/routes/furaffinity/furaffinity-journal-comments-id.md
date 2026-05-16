# Furaffinity - Journal Comments

## Coverage
`index-only`

## Route
- Namespace: `furaffinity`
- Namespace Name: `Furaffinity`
- Route Path: `/furaffinity/journal-comments/:id`
- Route Name: `Journal Comments`
- Example: `/furaffinity/journal-comments/10925112`
- URL: `furaffinity.net`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `TigerCubDen, SkyNetX007`
- Source Location: `journal-comments.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Journal ID


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `furaffinity.net/journal/:id`
- `target`: `/journal-comments/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/furaffinity/journal-comments/10925112",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "journal-comments.ts",
  "maintainers": [
    "TigerCubDen",
    "SkyNetX007"
  ],
  "name": "Journal Comments",
  "parameters": {
    "id": "Journal ID"
  },
  "path": "/journal-comments/:id",
  "radar": [
    {
      "source": [
        "furaffinity.net/journal/:id"
      ],
      "target": "/journal-comments/:id"
    }
  ],
  "topFeeds": [],
  "url": "furaffinity.net"
}
```
