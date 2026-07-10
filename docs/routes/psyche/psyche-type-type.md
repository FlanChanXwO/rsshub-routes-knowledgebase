# Psyche - Types

## Coverage
`index-only`

## Route
- Namespace: `psyche`
- Namespace Name: `Psyche`
- Route Path: `/psyche/type/:type`
- Route Name: `Types`
- Example: `/psyche/type/ideas`
- URL: `psyche.co`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `emdoe`
- Source Location: `type.ts`
- Source Module: `_None_`

## Description
Supported types: Ideas, Guides, and Films.

## Parameters
- `type`: Type


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
  - `psyche.co/:type`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "Supported types: Ideas, Guides, and Films.",
  "example": "/psyche/type/ideas",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "type.ts",
  "maintainers": [
    "emdoe"
  ],
  "name": "Types",
  "parameters": {
    "type": "Type"
  },
  "path": "/type/:type",
  "radar": [
    {
      "source": [
        "psyche.co/:type"
      ]
    }
  ],
  "topFeeds": []
}
```
