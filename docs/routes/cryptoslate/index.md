# CryptoSlate - News

## Coverage
`index-only`

## Route
- Namespace: `cryptoslate`
- Namespace Name: `CryptoSlate`
- Route Path: `/`
- Route Name: `News`
- Example: `/cryptoslate`
- URL: `cryptoslate.com`
- Language: `en`
- Categories: `finance`
- Maintainers: `pseudoyu`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/cryptoslate/index.ts')`

## Description
Get latest news from CryptoSlate.

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
  - `cryptoslate.com/`
- `target`: `/`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "Get latest news from CryptoSlate.",
  "example": "/cryptoslate",
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
  "module": "() => import('@/routes/cryptoslate/index.ts')",
  "name": "News",
  "parameters": {},
  "path": "/",
  "radar": [
    {
      "source": [
        "cryptoslate.com/"
      ],
      "target": "/"
    }
  ]
}
```
