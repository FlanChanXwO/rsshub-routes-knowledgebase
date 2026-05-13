# Decrypt - News

## Coverage
`index-only`

## Route
- Namespace: `decrypt`
- Namespace Name: `Decrypt`
- Route Path: `/`
- Route Name: `News`
- Example: `/decrypt`
- URL: `decrypt.co`
- Language: `en`
- Categories: `finance`
- Maintainers: `pseudoyu`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/decrypt/index.ts')`

## Description
Get latest news from Decrypt.

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
  - `decrypt.co/`
- `target`: `/`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "Get latest news from Decrypt.",
  "example": "/decrypt",
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
  "module": "() => import('@/routes/decrypt/index.ts')",
  "name": "News",
  "parameters": {},
  "path": "/",
  "radar": [
    {
      "source": [
        "decrypt.co/"
      ],
      "target": "/"
    }
  ]
}
```
