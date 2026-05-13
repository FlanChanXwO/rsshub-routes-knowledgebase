# Cointelegraph - News

## Coverage
`index-only`

## Route
- Namespace: `cointelegraph`
- Namespace Name: `Cointelegraph`
- Route Path: `/`
- Route Name: `News`
- Example: `/cointelegraph`
- URL: `cointelegraph.com`
- Language: `en`
- Categories: `finance`
- Maintainers: `pseudoyu`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/cointelegraph/index.ts')`

## Description
Get latest news from Cointelegraph with full text.

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
  - `cointelegraph.com/`
- `target`: `/`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "Get latest news from Cointelegraph with full text.",
  "example": "/cointelegraph",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "pseudoyu"
  ],
  "module": "() => import('@/routes/cointelegraph/index.ts')",
  "name": "News",
  "parameters": {},
  "path": "/",
  "radar": [
    {
      "source": [
        "cointelegraph.com/"
      ],
      "target": "/"
    }
  ]
}
```
