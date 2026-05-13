# Furaffinity - Journal Comments

## Coverage
`index-only`

## Route
- Namespace: `furaffinity`
- Namespace Name: `Furaffinity`
- Route Path: `/journal-comments/:id`
- Route Name: `Journal Comments`
- Example: `/furaffinity/journal-comments/10925112`
- URL: `furaffinity.net`
- Language: `en`
- Categories: `social-media`
- Maintainers: `TigerCubDen, SkyNetX007`
- Source Location: `journal-comments.ts`
- Source Module: `() => import('@/routes/furaffinity/journal-comments.ts')`

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
  "location": "journal-comments.ts",
  "maintainers": [
    "TigerCubDen",
    "SkyNetX007"
  ],
  "module": "() => import('@/routes/furaffinity/journal-comments.ts')",
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
  "url": "furaffinity.net"
}
```
