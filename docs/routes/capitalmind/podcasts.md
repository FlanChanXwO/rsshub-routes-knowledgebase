# Capitalmind - Podcasts

## Coverage
`index-only`

## Route
- Namespace: `capitalmind`
- Namespace Name: `Capitalmind`
- Route Path: `/podcasts`
- Route Name: `Podcasts`
- Example: `/capitalmind/podcasts`
- URL: `capitalmind.in`
- Language: `en`
- Categories: `finance`
- Maintainers: `Rjnishant530`
- Source Location: `podcasts.ts`
- Source Module: `() => import('@/routes/capitalmind/podcasts.ts')`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: true
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `capitalmind.in/podcasts`
- `target`: `/podcasts`

## Raw JSON
```json
{
  "example": "/capitalmind/podcasts",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportScihub": false
  },
  "location": "podcasts.ts",
  "maintainers": [
    "Rjnishant530"
  ],
  "module": "() => import('@/routes/capitalmind/podcasts.ts')",
  "name": "Podcasts",
  "path": "/podcasts",
  "radar": [
    {
      "source": [
        "capitalmind.in/podcasts"
      ],
      "target": "/podcasts"
    }
  ]
}
```
