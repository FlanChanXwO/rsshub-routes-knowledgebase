# Crossbell - Notes of character

## Coverage
`index-only`

## Route
- Namespace: `crossbell`
- Namespace Name: `Crossbell`
- Route Path: `/notes/character/:characterId`
- Route Name: `Notes of character`
- Example: `/crossbell/notes/character/10`
- URL: `crossbell.io/*`
- Language: `en`
- Categories: `social-media`
- Maintainers: `DIYgod`
- Source Location: `notes/character.ts`
- Source Module: `() => import('@/routes/crossbell/notes/character.ts')`

## Description
_None_

## Parameters
- `characterId`: N


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
  - `crossbell.io/*`
- `target`: `/notes`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/crossbell/notes/character/10",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "notes/character.ts",
  "maintainers": [
    "DIYgod"
  ],
  "module": "() => import('@/routes/crossbell/notes/character.ts')",
  "name": "Notes of character",
  "parameters": {
    "characterId": "N"
  },
  "path": "/notes/character/:characterId",
  "radar": [
    {
      "source": [
        "crossbell.io/*"
      ],
      "target": "/notes"
    }
  ],
  "url": "crossbell.io/*"
}
```
