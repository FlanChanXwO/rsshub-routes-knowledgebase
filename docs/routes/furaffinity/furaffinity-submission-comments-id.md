# Furaffinity - Submission Comments

## Coverage
`index-only`

## Route
- Namespace: `furaffinity`
- Namespace Name: `Furaffinity`
- Route Path: `/furaffinity/submission-comments/:id`
- Route Name: `Submission Comments`
- Example: `/furaffinity/submission-comments/24259751`
- URL: `furaffinity.net`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `TigerCubDen, SkyNetX007`
- Source Location: `submission-comments.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Submission ID


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
  - `furaffinity.net/view/:id`
- `target`: `/submission-comments/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/furaffinity/submission-comments/24259751",
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
  "location": "submission-comments.ts",
  "maintainers": [
    "TigerCubDen",
    "SkyNetX007"
  ],
  "name": "Submission Comments",
  "parameters": {
    "id": "Submission ID"
  },
  "path": "/submission-comments/:id",
  "radar": [
    {
      "source": [
        "furaffinity.net/view/:id"
      ],
      "target": "/submission-comments/:id"
    }
  ],
  "topFeeds": [],
  "url": "furaffinity.net"
}
```
