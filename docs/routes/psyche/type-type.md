# Psyche - Types

## Coverage
`index-only`

## Route
- Namespace: `psyche`
- Namespace Name: `Psyche`
- Route Path: `/type/:type`
- Route Name: `Types`
- Example: `/psyche/type/ideas`
- URL: `psyche.co`
- Language: `en`
- Categories: `new-media`
- Maintainers: `emdoe`
- Source Location: `type.ts`
- Source Module: `() => import('@/routes/psyche/type.ts')`

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
  "location": "type.ts",
  "maintainers": [
    "emdoe"
  ],
  "module": "() => import('@/routes/psyche/type.ts')",
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
  ]
}
```
